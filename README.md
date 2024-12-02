 # Java-Project
Project
 

 # ❤️ Heart Shape yousing Java loop 

 
  ![GraciasGIF (2)](https://github.com/user-attachments/assets/843c42c5-c56b-4f81-afae-5c85aea5ef9f)
    
   This Java program generates a heart pattern made of asterisks (`*`). Here’s a breakdown of how it works:

### Code Explanation:

1. **Input Handling:**
   - The program prompts the user to enter a value (`n`), which determines the size of the heart pattern.

2. **First Loop (Top Part of the Heart):**
   - The outer loop (`for (i = n / 2; i <= n; i += 2)`) generates the top part of the heart.
   - Inside the loop:
     - **Spaces Before the First Half of the Heart:** `for (j = 1; j < n - i; j += 2)`
     - **Asterisks for the First Half of the Heart:** `for (j = 1; j <= i; j++)`
     - **Spaces Between the Two Halves:** `for (j = 1; j <= n - i; j++)`
     - **Asterisks for the Second Half of the Heart:** `for (j = 1; j <= i; j++)`

3. **Second Loop (Bottom Part of the Heart):**
   - The loop (`for (i = n; i >= 1; i--)`) generates the lower triangular part of the heart.
   - Inside the loop:
     - **Spaces Before the Triangular Part:** `for (j = i; j < n; j++)`
     - **Asterisks for the Triangular Part:** `for (j = 1; j <= (i * 2) - 1; j++)`

4. **Output Example:**
   If the user enters `n = 6`, the output will look like this:

```
     **     **
    ****   ****
   ****** ******
    ***********
     *********
      *******
       *****
        ***
         *
```

### Customization:
- You can adjust `n` to increase or decrease the size of the heart.
- This pattern works best with even values of `n` to maintain symmetry.

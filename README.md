## Libft
    
![](assets/cover.png)

`Libft` is the first project at **School 42**. This library re-codes standard C library functions and includes key utilities for future projects.

### How to Use

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/iTsLhaj/Libft.git
    ```
2.  **Compile the library:**
    ```bash
    cd Libft
    make
    ```
    This creates the static library file `libft.a`.

3.  **Link it to your project:**
    ```bash
    cc your_project.c -L. -lft -o your_program
    ```
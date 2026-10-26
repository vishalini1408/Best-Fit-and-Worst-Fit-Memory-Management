# Experiment 12: Best Fit and Worst Fit Memory Management

## Aim
To compare Best Fit and Worst Fit memory allocation policies using the same memory blocks and application sizes.

## Algorithm
1. Initialize the application sizes as 45 MB, 75 MB, and 100 MB.
2. Run Best Fit using memory blocks of 50 MB, 120 MB, and 80 MB.
3. Reset the memory blocks.
4. Run Worst Fit using the same block sizes.
5. Find a suitable block for each application according to the selected policy.
6. Allocate the application and reduce the remaining block size. If no block fits, print `WAIT`.
7. Display both allocation results.

## C Program
File: `compare.c`

## Compile and Run
```bash
gcc compare.c -o compare
./compare
```

## Expected Result
Best Fit allocates all three applications in this example. Worst Fit allocates the first two applications; the 100 MB application cannot be allocated.

## Output
See `output.png` for the output image extracted from the lab manual, Experiment 12, Figure 3.

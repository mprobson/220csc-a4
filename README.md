# A4. Matrix Multiply

Due Date: 11/5 at midnight

## Instructions

Implement the matrix multiply (matmul) A * B = C algorithm in three variations:

1. CPU Matrix Multiply
2. GPU Matrix Multiply
3. GPU Tiled Matirx Multiply
4. GPU cuBLAS Library Call

As before, you should collect timing data and analyze the results for increasing
matrix sizes. That is, at what point does the tiled approach pay off in terms
of computational time/speed?

## Reflection Questions

0. Analyze your results, when does it make sense to use the various approaches?
1. How did your speed compare with cuBLAS
2. What went well with this assignment?
3. What was difficult?
4. How would you approach differently?
5. Anything else you want me to know?

## Submission
- [ ] Code
  - [ ] CPU
  - [ ] GPU
  - [ ] Tiled
- [ ] Runtimes/profiled code
- [ ] Graph
- [ ] Reflection

## Peer Feedback

After the assignment is due,
you will be randomly assigned to review another student's submission.
This will be as a pull request (PR).
You should look at the results, explanations, code, etc for
understandability, readability, style, etc and provide
any constructive or positive insights.

## Updating the Assignment

To update this assignment as changes are made,
a new PR will be generated.
You can find the tab [here](../../pulls).
On that page you can merge the pull request to get the update instructions.
This may invovle rebasing or merging your contributions, reach out
if you need help with this.

## Debugging

If you encounter errors, I recommend two approahces:

1. Adding print statements both inside your kernel function
   as well as outside.
   This can include: ` ` to catch any cuda errors.

memcheck

print statements

## Extras

4. Row/cache/conflict aware matrix multiply
1. Utilize `malloc`, `cudaMalloc`, and `cudaMemcpy`

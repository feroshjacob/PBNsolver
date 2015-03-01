PNBsolver: A Domain-Specific Language for Modeling Parallel N-body Problems
---------------------------------------------------------------------------

With the advent of multicore processors, parallel computation has become a necessity for next generation applications. It is often a tedious task
 for domain users to optimize their programs for a specific platform, algorithm, and problem size. We believe that domain users should be freed 
from this task and they should be equipped with tool support to reuse the optimized solutions written by expert parallel programmers. In this project,
 we introduce a two-stage modeling approach that allows domain users to express the problem using domain constructs and reuse the available optimized 
solutions. This approach has been applied successfully to N-body problems using a domain-specific language called PNBsolver, which allows domain users
 to specify the computations in an N-body problem without any implementation or platform-specific details. Using the PNBsolver, the domain users are 
allowed to control the platform and implementation of the generated code. The accuracy and execution time of the generated code can also be fine-tuned 
based on the parameters provided in PNBsolver. We have included in this paper, some of the common N-body interactions showing how it can be implemented 
using PNBsolver. Please find more details in the PDF file below.

More information is available <a href="https://sites.google.com/site/nbodysolver/">here</a>

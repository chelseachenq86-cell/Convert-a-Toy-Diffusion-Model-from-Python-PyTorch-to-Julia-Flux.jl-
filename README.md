# Convert-a-Toy-Diffusion-Model-from-Python-PyTorch-to-Julia-Flux.jl-
This project involves translating a small diffusion model named "smalldiffusion", which was written in Python and using the PyTorch framework, into the Julia programming language and implementing it using the learning framework Flux.jl of Julia.
The entire project can be divided into three main parts: 

Code translation: Convert the key logic of the Python project, including the model architecture, noise scheduler, training loop, and sampling logic, into Julia code (this task does not include the conversion of the UNet structure). 

Explanation and Comparison: Clearly explain in the report the specific choices made when converting the code for the Julia language and the Flux.jl framework, and emphasize the differences between these implementations and those in Python/PyTorch. 

Testing and Validation: After the conversion is completed, use a toy dataset (such as the "Dino" dataset from Datasaurus Dozen or the "Swissroll" dataset) to train the Julia version of the model, and call the model to generate new samples to verify its correctness.

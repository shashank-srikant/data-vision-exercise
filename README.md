# An exercise in data analysis and image processing

This is a small exercise in the kinds of skills that may be required of you.  
The goal here is to evaluate how well you understand the problem, scope it, come up with a strategy to solve it, and execute it.  
More formally, we will look for the following in our evaluation:

## Expected deliverables and evaluation criteria
- Have a working prototype of the task described below.
- (We will) assess how well you scope and assess the different components involved which will solve this problem
- Assess how you divide your labor into the components you identify, and how quickly you're able to prototype and finish implementing those components. Remember, there's a time budget of a few days.
- Assess how you resolve situations when you're stuck.
- Assess how well you communicate and let all stakeholders know of your progress.

## Task 1 - Gather data
Take photographs of five common products around you which someone may be interested in selling on an e-commerce platform. Example: a pen knife, knife, a shirt, etc.
These product images should satisfy the following conditions:
- the photo should be taken from a regular smart phone camera.
- the product should be in the center, and cover most of the image.
- it should have a uniformly colored background.
- it should be captured under regular (but good) lighting in your surroundings. For example, you don't need to have studio-grade lighting; just a table lamp so that the product is well lit.

A sample image has been stored in `/data`. Upload your images to `/data` as well.

## Task 2
Use a state-of-the-art image processing model to convert the photos in `/data` to "studio quality".  
Some examples of studio quality images have been provided in `/data/studio-quality`.
Studio-quality images will generally have the following properties:
- a very high resolution of the product in the center
- sharpness - sharply defined edges, no blurring
- a white or blurred background
- 

## Task 3
In addition to the images being studio quality, add a hand holding up each of the products in your photos.  
If the product is too large, consider resizing it so that it will look natural for a hand to hold it up.  
An example has been provided in `data/studio-quality-with-hand`

## Instructions to submit your work
- Do not fork this repo. Work on a local copy. Make it a habit to push changes upstream to your repo as frequently as feasible.
- Use `Python3.8+` for this work.
- We greatly value reproducability of results. Use `conda` to create an environment and set up your repository. 
- Use a `.gitignore` file to ensure you are not adding junk files to the repo.
- Have a `./src/` folder containing the source.
- Have a `./env/` folder containing the Conda environment file you create for this project.
- Have a `./data/` folder containing all the data your source accesses.
- Have a `./tests/` folder to write out unit tests for key functions. Look up the `unittest` package in Python if you haven't used it before. Also, not every function you write needs to be tested---exercise your judgement and prioritize which function you want tested.
- Keep updating this README with instructions which will help with the reproducability of your work/results.  
- The topmost section of your readme file should be titled `Approach`. In this section, concisely describe the overeall approach you considered to solve this problem. Describe the general strategy you used, the key tools you considered, the different metrics you considered to evaluate your work, and any other detail relevant to the task goals and the evaluation criteria mentioned above.

Focus on getting the core functionality right first, and have a working prototype of your solution.

On completing the task, share with us the URL to your repo local to your account.

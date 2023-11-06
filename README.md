# An exercise in data analysis and image processing

This is a small exercise in the kinds of skills that may be required of you.  
The goal here is to evaluate how well you understand the problem, scope it, come up with a strategy to solve it, and execute it.  
More formally, we will look for the following in our evaluation:

## Expected deliverables and evaluation criteria
- Have a working prototype of the task described below.
- (We will) assess how well you scope and assess the different components involved which will solve this problem
- Assess how you divide your labor into the components you identify, and how quickly you're able to prototype and finish implementing those components. Remember, there's a time budget of a few days.
- Assess how you resolve situations when you're stuck.
- Assess how well you communicate and let all stakeholders know of your progress. We emphasize constant communication over receiving no communication for days, and just seeing a dump of the results on the day of your submission. This has multiple drawbacks: (1) it gives us no insight into the process you employ to evaluate a problem and come up with a solution. (2) it gives us no room to help you in case you're stuck on any step. Consider this to be a task you will receive on your job - demonstrate to us how you will work on the task in such a setting.

## Task 1 - Gather data
Take photographs of five common products around you which someone may be interested in selling on an e-commerce platform. Example: a pen knife, knife, a shirt, etc.
These product images should satisfy the following conditions:
- the photo should be taken from a regular smart phone camera.
- the product should be in the center, and cover most of the image.
- it should have a uniformly colored background.
- it should be captured under regular (but good) lighting in your surroundings. For example, you don't need to have studio-grade lighting; just a table lamp so that the product is well lit.

A sample image has been stored in `./data/products/`. Upload your images to `./data/products/` as well.

## Task 2
Use a state-of-the-art image processing model to convert the photos in `./data/products/` to "studio quality".  
Some examples of studio quality images have been provided in `./data/products-studio-quality/`.
Studio-quality images will generally have the following properties:
- High Resolution: Studio images are typically captured with high-resolution cameras, resulting in crisp and detailed images. The high resolution allows for large prints and digital use without loss of quality.
- Subject Isolation: Studio photography often uses shallow depth of field to isolate the subject from the background, creating a clear focus on the subject.
- Clean and Controlled Backgrounds: Studio images typically feature plain and uncluttered backgrounds that are carefully controlled and lit to make the subject stand out.
- Perfect Lighting: Studio photographers use precise lighting setups to sculpt the subject, eliminate harsh shadows, and create the desired mood. This may involve softboxes, diffusers, reflectors, and other lighting accessories.
- Precise Focus and Sharpness: Studio photographers use manual focus and high-quality lenses to ensure precise control over focus, resulting in tack-sharp images.
- Texture and Detail: Studio images bring out texture and fine detail in the subject, whether it's a product, a person's skin, or any other subject.
- Minimal Noise Reduction: While noise reduction is essential, excessive noise reduction can lead to a loss of detail. In studio photography, noise reduction is applied judiciously to preserve texture and detail.
- Professional Retouching: Post-processing is often applied to studio images to enhance their quality, including retouching for skin, removal of imperfections, and color correction.
- Consistency: Studio photographers aim for consistent quality across a series of images, especially in commercial photography. This ensures that all product shots or portfolio images maintain a uniform style and quality.
- Appropriate Depth: Studio images can achieve a sense of three-dimensionality by carefully controlling lighting to highlight form and depth in the subject.

Which models might work best for such a task?  
Will you need GPU compute to achieve the desired final quality, or can you achieve it with a decent CPU?  
Is it possible to use multiple models - each providing a particular enhancement?  
In case of multiple models being suitable, which one model would you go for which might achieve the best possible outcome?

## Task 3
In addition to the images being studio quality, add a hand holding up each of the products in your photos.  
If the product is too large, consider resizing it so that it will look natural for a hand to hold it up.  
An example has been provided in `./data/products-studio-quality-with-hand/`

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

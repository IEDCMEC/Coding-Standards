# Some important things to be noted while working in IEDC  tech team :

<p float="left">
  <img width="325" height="150" alt="image" src="https://user-images.githubusercontent.com/75477017/188143031-dee759b6-9b72-4821-adf5-3059b2116eac.png">
  <img width="325" height="150" alt="image" src="https://user-images.githubusercontent.com/75477017/188143098-7d2fed7b-5282-454c-9346-621192bc7156.png">
 <img width="325" height="150" alt="image" src="https://user-images.githubusercontent.com/75477017/188143164-7dc58098-869f-46cd-bcbb-96d0ff7b840e.png">
</p>

1. Folder Structure:

2. Naming conventions:
    - React UI component’s names should be PascalCase. <br>
    Eg: LandingPage.js
    - All other helper files should be camelCase. <br>
    Eg: requestData.js
    - All the folder names should be camelCase
    - CSS files should be named the same as the component PascalCase.
    - Font imports should be done in index.css

3. Codestyle:
    - No hardcoded values, use constants values.
    - Avoid multiple if/else and nested blocks.
    - No commented out code.
    - Add necessary comments.
    - Remove all console.log()
    - Do not import the modules in the component file unless they are required, since it can affect the overall performance of the website
    - Always follow the exact design provided in the figma file and develop the website accordingly.
    - While making boxes or any other large structure do not use ‘px’ as the unit for width and height, always    use ‘rem’ or ‘%’ for the same(try to use rem more).
    ‘px’ can be used in places for fine adjustments like border radius and all.
    - Always terminate the React app successfully without warnings or errors.

4. CSS:
    - Use classNames everywhere. Do not use html tags to style.
    - Use flex boxes and media queries for making the contents responsive.
    - Avoid absolute positioning.
    - Use BEM CSS convention of naming in css and we can avoid module.css since it’s really difficult. While naming classes try to include component names also 
    Eg: if we have a box in the faq section then we can name the className as faq__box rather than simply describing it as box
    - Avoid !important unless absolutely necessary.
    - Avoid inline styles unless necessary.
    - While styling mui components try to make use of 'sx-props' methods rather than creating multiple 'divs' or explicit styling of classnames provided by the same.

5. Format of working:
    - Initially fork the repo and create a copy in your respective account.
    - Clone the repository to your local machine.
    - Make the changes in your code that you are asked to do so.
    - After performing the required changes, chacke whether you forked copy is up to date with the original copy. If it is not, then press the 'syn fork' option provided in your forked copy.
    - Pull the new changes to your local repository.
    - Now check whether there is any kind of conflicts in the local code. If it's perfectly working then add all changes, commit and push your code to forked repository.
    - Now open the 'contribute to' option in forked copy and send the pull request to the source repository with required message. 
    - Do not merge the pull request even if you have access to do so.




    <i>Happy Coding....:))</i><br>
    <i>Team IEDC MEC</i>

# SVG-Logo-Maker
 
 [![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)
## Description
Ever wanted a logo thats able to scale to any size big or small? 
Takes too long to manually make the SVG? Well now you got the solution to both those problems! 
With this SVG Logo Maker you can generate an SVG logo with your choice of shape (circle, square, or triangle), shape color, text (limit of 3 characters), and text color. 
Shape and text colors can be chosen using color keywords or hexadecimal numbers.
[Demo](https://github.com/LockedJCE/SVG-Logo-Maker/assets/163614828/760ce496-2b39-40ee-9f9f-7996bd2417e6)

## Table of Contents
  * [Acceptance-Criteria](#acceptance-criteria)
  * [Installation](#installation)
  * [Usage](#usage)
  * [Licenses](#licenses)
  * [Contributing](#contributing)
  * [Tests](#tests)
  * [Questions](#questions)
  * [Credits](#credits)
## Acceptance-Criteria
    GIVEN a command-line application that accepts user input
    WHEN I am prompted for text
    THEN I can enter up to three characters
    WHEN I am prompted for the text color
    THEN I can enter a color keyword (OR a hexadecimal number)
    WHEN I am prompted for a shape
    THEN I am presented with a list of shapes to choose from: circle, triangle, and square
    WHEN I am prompted for the shape's color
    THEN I can enter a color keyword (OR a hexadecimal number)
    WHEN I have entered input for all the prompts
    THEN an SVG file is created named `logo.svg`
    AND the output text "Generated logo.svg" is printed in the command line
    WHEN I open the `logo.svg` file in a browser
    THEN I am shown a 300x200 pixel image that matches the criteria I entered
  ## Installation
    Download Node.js and install jest
  ## Usage
    Invoke the application by typing "node index.js" in the terminal's command line. You will be asked a series of questions before your logo is generated. 
    If you do not enter a valid color keyword or hexadecimal number, you will be asked to try again. If your text contains more than 3 characters, you will be asked to try again. 
    Once all questions have been  answered with accepted values, your new logo will be generated with the file name 'logo.svg' in the 'examples' folder. Refer back to the video posted in the description as needed.
  ## Licenses
  This project is covered under the MIT license. To learn more about what this means, click the license button at the top.
  MIT License

    Copyright (c) 2024 Jensen

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.
  ## Contributing
  Finished project so no contributions needed but thank you.
  ## Tests
  Each shape class (Circle, Square, and Triangle) is tested for a render() method that returns a string for the corresponfing SVG file matching color and text requests. Type "npm test" in the command line and Jest will run all three tests.
  ## Questions
  Have questions about this project?  
  GitHub: https://github.com/LockedJCE  

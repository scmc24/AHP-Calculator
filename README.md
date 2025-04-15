# AHP Phone Selector

This application helps you select the ideal phone from a list of alternatives using the Analytic Hierarchy Process (AHP) technique. The AHP is a structured methodology for organizing and analyzing complex decision problems.

## Features

- Utilizes the AHP technique for decision-making
- Configurable alternatives (phones) and criteria
- Pairwise comparison matrices for criteria and alternatives
- Calculation of priority vectors and consistency ratios
- Visual representation of results with bar charts
- User-friendly interface

## How It Works

1. The application uses predefined pairwise comparison matrices based on preferences for:
   - Criteria (Memory, Storage, CPU frequency, Price, Brand)
   - Alternatives with respect to each criterion

2. It calculates weights for each criterion and alternative using the eigenvector method

3. It calculates the final scores for each alternative by aggregating the weighted scores

4. It checks the consistency of the decision-making process using the Consistency Ratio (CR)

5. It displays the results as rankings and a bar chart

## How to Run

This is a web application that runs directly in your browser. No installation or dependencies are required.

### Option 1: Run directly from the repository

1. Clone this repository or download the source code
2. Open `index.html` in any modern web browser

### Option 2: Run from a local web server

1. Clone this repository or download the source code
2. If you have Python installed, navigate to the project directory and run:
   - Python 3: `python -m http.server`
   - Python 2: `python -m SimpleHTTPServer`
3. Open your browser and navigate to `http://localhost:8000`

## Usage

1. The application comes with default alternatives (phones) and criteria
2. You can modify the alternatives and criteria in the input fields
3. Click "Calculate Best Phone" to run the AHP algorithm
4. The results will show the criteria weights, consistency check, final rankings, and your ideal phone
5. The bar chart visualizes the scores for each alternative

## Implementation Details

- The application is built using pure HTML, CSS, and JavaScript
- No external libraries or dependencies are required
- The pairwise comparison matrices are predefined based on the developer's preferences
- The consistency check ensures the reliability of the decision-making process

## Customization

You can customize the application by:
- Modifying Random Index values for consistency ratio calculation

## Project Structure

- `index.html`: The main HTML file containing the application
- `README.md`: This documentation file

## License

This project is open-source and available under the MIT License.

## Author

scmc24 - manuelsokoudjou@gmail.com
# Coupon Acceptance Analysis

This project analyzes the acceptance rates of various types of coupons based on different user attributes and conditions. The data used in this analysis comes from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk.

## Project Structure

## Data Description

The attributes of this data set include:

1. **User attributes**
    - Gender: male, female
    - Age: below 21, 21 to 25, 26 to 30, etc.
    - Marital Status: single, married partner, unmarried partner, or widowed

2. **Driving attributes**
    - Location of the user, destination, and the venue, with the distance between each two places marked with time of driving.
    - Weather: sunny, rainy, or snowy
    - Temperature: 30F, 55F, or 80F
    - Time: 10AM, 2PM, or 6PM
    - Passenger: alone, partner, kid(s), or friend(s)

3. **Coupon attributes**
    - Time before it expires: 2 hours or one day

## Analysis

The analysis includes the following steps:

1. **Data Cleaning**: Handling missing values, renaming columns, and converting data types.
2. **Data Visualization**: Using matplotlib and seaborn to create various plots to visualize the data.
3. **Statistical Analysis**: Calculating acceptance rates for different groups and conditions.

## Installation

To run the analysis, follow these steps:

1. Clone the repository:
    ```sh
    git clone <repository-url>
    ```
2. Navigate to the project directory:
    ```sh
    cd Data_Analysis_Coupon
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```
4. Open `prompt.ipynb` in Jupyter Notebook or any compatible environment.
5. Run the cells in the notebook to perform the analysis.

## Results

The results of the analysis are visualized using various plots, including bar plots, pie charts, and histograms. These plots highlight the differences between customers who did and did not accept the coupons based on different attributes and conditions.

## License

This project is licensed under the MIT License.

## Acknowledgments

- The data used in this project comes from the UCI Machine Learning repository.
- The survey data was collected via Amazon Mechanical Turk.

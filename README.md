# Dowell-sample-size-calculation

The Sample Size Calculator API is a tool designed to assist researchers, analysts, and data scientists in determining the appropriate sample size for a given population, variance, error tolerance, and confidence interval. This API streamlines the process of calculating sample sizes for various statistical analyses, ensuring that your studies are statistically sound and reliable.

## Getting Started

To begin using the Sample Size API, follow these steps:
1. ```Review the API Documentation:``` Familiarize yourself with the available endpoints, request parameters, and response formats outlined in this documentation.
2. ```API Requests:``` Make API requests using the provided endpoint and necessary input parameters:
- ```Endpoint:```

    ```http://100102.pythonanywhere.com/sample-size/```

- ```Input Parameters:```

    ```1. Variance```: A measure of how much the values in a dataset differ from the mean. It indicates the spread or dispersion of the data points.

    ```2. Error Tolerance```: The maximum allowable difference between the true population parameter and the estimated parameter based on the sample.  It reflects the level of precision desired in the study's results.

    ```3. Population Size```: The total number of individuals or elements in the entire population being studied. It is the entire group from which a  sample is drawn.

    ```4. Confidence Interval```: A range within which the true population parameter is expected to lie with a certain level of confidence. It is  often expressed as a percentage.

3. ```Response Format:``` Upon making an API request, you will receive a detailed response containing the following information:

- ```method_used:``` The specific statistical method applied for sample size calculation.Methods used are:
    - Slovin's Method- When the variance is not provided.
    - Sample size generation using population size,  variance, error and confidence interval (z score).
- ```sample_size:``` The recommended sample size for the study.
- ```computation_time:``` The time taken for the computation process.

## Documentation and Support

For detailed API documentation, including endpoint descriptions, request and response examples, and authentication details, please refer to the [API Documentation](https://documenter.getpostman.com/view/27523601/2s9Y5ZvhJo).

If you encounter any issues, have questions, or need assistance with the Dowell Sample Size API, please contact our support team.

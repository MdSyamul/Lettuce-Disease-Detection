
# Lettuce Disease Detection

Welcome to the **Lettuce Disease Detection** repository! This project focuses on training Yolo11 model to accurately classify diseases affecting lettuce plants. Early detection and classification are crucial for preventing the spread of diseases and ensuring healthy crop yields.

## Project Overview
The Lettuce Disease Detection project is a part of our indoor farming project, aims to provide an automated solution for disease identification, helping in timely intervention and treatment.

## Getting Started
To run the training script, follow these steps:

1. **Clone the Repository**: Start by cloning this repository to your local machine.

    ```bash
    git clone https://github.com/MdSyamul/lettuce-disease-detection.git
    ```
    
2. **Set Up a Virtual Environment**: It’s recommended to use Python 3.12.3 for compatibility.

    ```bash
    python3 -m venv lettuce_env
    source lettuce_env/bin/activate  # On Windows use: lettuce_env\Scripts\activate
    ```

3. **Install PyTorch**: Ensure you install a version of PyTorch compatible with your CUDA version. Follow the instructions at [PyTorch's official installation guide](https://pytorch.org/get-started/locally/) to install the correct version.

4. **Install Ultralytics**: This package includes necessary tools for training.

    ```bash
    pip install ultralytics
    ```

5. **Run the Training Script**: Open the `train.ipynb` notebook in Jupyter and run the cells to begin training.

    ```bash
    jupyter notebook train.ipynb
    ```


## Results
The training process will generate logs and model checkpoints, which can be used to evaluate the model's performance and make further improvements.

## Contributing
Contributions to the Lettuce Disease Detection project are welcome. If you have any suggestions or improvements, please create a pull request or open an issue.
## Funding and Acknowledgments

This project is funded by the **Research Center of Shahjalal University of Science and Technology**. We express our sincere gratitude for their support and resources, which have been instrumental in advancing this research.

## Contact

For questions, collaborations, or further information, please contact:

- **Project Lead**: Md. Syamul Bashar
- **Email**: md.syamul-mee@sust.edu
- **Institution**: Department of Mechanical Engineering, Shahjalal University of Science and Technology

## License

This project will be licensed under the [MIT License](LICENSE) upon release.

---

Stay tuned for updates! We are excited to share our work with the community and contribute to advancements in agricultural technology.

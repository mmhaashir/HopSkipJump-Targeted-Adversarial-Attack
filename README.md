# HopSkipJump Targeted Adversarial Attack

## Introduction <a name="intro"></a>

This project demonstrates how to perform a targeted attack using the HopSkipJump attack technique while injecting noise from a separate image into the target image. The objective is to craft an adversarial image that is misclassified by a machine learning model. We use Python and various libraries, including TensorFlow and ART, for this purpose.

![dav_image](https://techs0uls.files.wordpress.com/2020/06/qeba.png?w=1024)

## Table of Contents

- [**Introduction**](#intro)
- [**Dependencies**](#dep)
- [**Installation**](#install)
- [**Usage**](#usage)
- [**Results**](#results)
- [**Contribution**](#contr)
- [**Conclusion**](#conc)

## Dependencies <a name="dep"></a>

To run this code, you will need the following Python libraries:

  - TensorFlow (as tf)
  - Adversarial Robustness Toolbox (ART)
  - Matplotlib (as matplotlib)
  - Requests
  - NumPy
  - PIL (Python Imaging Library)

## Dataset

The dataset can be downloaded [here](http://icvl.ee.ic.ac.uk/vbalnt/hpatches/). Download the `hpatches-sequence-release.tar.gz`

## Installation <a name="install"></a>

1. Clone the repository:
   `git clone https://github.com/mmhaashir/HopSkipJump-Targeted-Adversarial-Attack.git`
   
3. Install the required dependencies:
   `pip install tensorflow adversarial-robustness-toolbox matplotlib requests numpy pillow`

## Usage <a name="usage"></a>

To run the HopSkipJump Adversarial Attack:

  1. Open the Jupyter Notebook or Python script provided in the project directory.

  2. Load the pre-trained ImageNet model using TensorFlow.

  3. Select a target image that you want to attack and an image acting as the noise you wish to inject.

  4. Run the attack. The code will generate adversarial images iteratively and display it alongwith the misclassified output.

## Results <a name="results"></a>

After running the attack, you will observe that the adversarial image, created by injecting noise into the target image, is misclassified by the pre-trained machine learning model. The generated adversarial image will be displayed, demonstrating the success of the targeted attack.

## Contributing <a  name="contr"></a>

Contributions to this project are welcome. If you have suggestions or improvements, please open an issue or submit a pull request.

## Conclusion <a name="conc"></a>

This project showcases the use of TensorFlow and the Adversarial Robustness Toolbox (ART) to perform a HopSkipJump targeted attack while injecting noise from a separate image into the target image. Such attacks emphasize the need for robust machine learning models and highlight potential security risks associated with adversarial examples.

Feel free to experiment with different images, noise patterns, and attack parameters to gain a deeper understanding of targeted attacks and their impact on machine learning systems.

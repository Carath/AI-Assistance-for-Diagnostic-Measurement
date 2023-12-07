# AI Assistance for Diagnostic Measurement

Neural network code for the [*Non Destructive Diagnostic Measurement Methods for HF RFID Devices with AI Assistance*](https://ieeexplore.ieee.org/document/10334483) IEEE paper.


The provided notebooks are to be used in [*Google Colab*](https://colab.research.google.com/) :
- ``` AI-Assistance-for-Diagnostic-Measurement.ipynb ``` trains several neural networks on the given dataset, and evaluate their performances. Note that this takes approximately one hour to run.
- ``` Inference-and-robustness-tests.ipynb ``` confirms the median model accuracy on new data, and tests its robustness on noisy data. Additionally, a quantized heatmap produced by the model giving faster inference times is tested.

Note: the provided *requirements.txt* file lists the versions of the used Python packages. To reproduce the environment used in those notebooks, one can run: ``` pip install -r requirements.txt ```

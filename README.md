<p align="center">
<img width="300" src="https://github.com/ML-KULeuven/dtaianomaly/blob/main/docs/logo/readme.svg" alt=""/>
</p>

<h1 align="center">InTimeAD</h1>
<h2 align="center">Time series anomaly detection</h2>

> Try ``InTimeAD`` now: https://intimead.cs.kuleuven.be!

``InTimeAD`` is an interactive web application build on top of [``dtaianomaly``](https://github.com/ML-KULeuven/dtaianomaly) that provides access to more than 30 state-of-the-art time series anomaly detection models. InTimeAD is intended to explore the performance of existing as well as custom anomaly detection models in an interactive, hands-on manner. By lowering the entry bar, we support practitioners overwhelmed by the large number of existing techniques, while providing a platform for researchers to rapidly analyze their novel anomaly detection algorithms. 

## Acknowledgments

``InTimeAD`` has been accepted at AAAI 2026, but is not yet published. If you find this work useful for your work, we would appreciate the following citation:
```bibtex
@article{carpentier2026intimead, 
    author={Carpentier, Louis and Meert, Wannes and Verbeke, Mathias}, 
    title={InTimeAD: Interactive Time Series Anomaly Detection}, 
    journal={Proceedings of the AAAI Conference on Artificial Intelligence}, 
    year={2026}, 
}
```
> Carpentier, L., Meert, W., Verbeke, M. (2026). InTimeAD: Interactive Time Series Anomaly Detection. Proceedings of the AAAI Conference on Artificial Intelligence.

## Usage

The easiest way to use ``InTimeAD`` is through the online application: https://intimead.cs.kuleuven.be.

Alternatively, it is possible to run the ``InTimeAD`` in a local host. First, run the following command to install ``InTimeAD`` (we recommend using a virtual environment):
```bash
pip install git+https://github.com/ML-KULeuven/ImtimeAD
```
Then, you can start a localhost by running the following command in the terminal:
```bash
InTimeAD
```
or by executing the following Python script:
```python
import in_time_ad
in_time_ad.run()
```

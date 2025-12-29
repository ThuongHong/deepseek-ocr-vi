# DeepSeek-OCR: Vietnamese Handwriting Recognition

DeepSeek-OCR is a fine-tuned OCR model designed for recognizing handwritten Vietnamese text. This repository contains the code, data, and resources for training, evaluating, and fine-tuning the model.

## Features

- Fine-tuned on the UIT-HWDB dataset for Vietnamese handwriting recognition.

- Achieves state-of-the-art performance with significant improvements in Character Error Rate (CER).

- Includes scripts for training, evaluation, and visualization of results.

## Repository Structure

- `data/`: Contains training and testing data.

- `notebooks/`: Jupyter notebooks for exploratory data analysis, training, and evaluation.

- `report/`: LaTeX files for generating the project report.

- `src/`: Source code for model training and evaluation.

## Quick Start

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ThuongHong/deepseek-ocr-vi.git
   cd deepseek-ocr-vi
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

### Usage

- **Fine-tuning:** Use the `notebooks/finetuning.ipynb` notebook to fine-tune the model on your dataset.

- **Evaluation:** Evaluate the model using `notebooks/eval-baseline.ipynb` and `notebooks/eval-finetuned.ipynb`.

- **Visualization:** Compare results and visualize metrics using `notebooks/compare_results.ipynb`.

## Results

The fine-tuned model achieved a 95.26% reduction in CER compared to the baseline model. For detailed results, refer to the `report/` directory.

## License

See the [LICENSE](LICENSE) file for details.

## References

- [Unsloth](https://unsloth.ai/)
- [UIT-HWDB Dataset](https://github.com/nghiangh/UIT-HWDB-dataset.git)

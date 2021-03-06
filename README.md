# chaos2order
This is a small project to generate image frames of three sorting algorithms (Heap sort, Quick sort, Bubble sort) in order to visualize how they work.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
- Python 3.6
- PIP package manager

### Installing
Clone the repository
```
git clone git@github.com:FedericoJurio/SortingAlgorithmVisualization.git
```

Access to the project directory
```
cd SortingAlgorithmVisualization
```
Install dependencies
```
pip install -r requirements.txt
```

## Usage
```
python src/sorter.py -algorithm {name}
```
Note: the allowed values for name are `bubble`, `heap`, and `quick`

## Samples
The following samples were created using the output frames and [ffmpeg](https://ffmpeg.org/).

| Bubble sort | Heap sort | Quick sort |
| --- | --- | --- |
| ![Bubble sort](https://github.com/FedericoJurio/chaos2order/blob/master/sample/bubble.gif) | ![Heap sort](https://github.com/FedericoJurio/chaos2order/blob/master/sample/heap.gif) | ![Quick sort](https://github.com/FedericoJurio/chaos2order/blob/master/sample/quick.gif) |

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

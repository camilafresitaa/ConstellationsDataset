# Constellations Dataset
This dataset contains structured definitions of constellations based on HR (Harvard Revised) star numbers.  
Each constellation is represented by a **sequence of stars that defines how to connect them** to form its visual shape in the sky.

It is designed to be compatible with the [Yale Bright Star Catalogue (YBSC)](http://tdc-www.harvard.edu/catalogs/bsc5.html), allowing easy integration with star data for visualizations, simulations, or educational projects.

## Format
The dataset is provided in CSV format with the following columns:

- **`Name`**: Name of the constellation.
- **`SequenceLength`**: Number of elements in the HR sequence (not necessarily unique stars).
- **`s01`** to **`s41`**: Ordered HR numbers that define the line path for drawing the constellation.

**Note:** Repeated HR numbers are intentional and represent line returns or junctions.

## License
This dataset is licensed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).  
You are free to use, modify, and distribute it, as long as you provide proper credit.

# Julia-Playground
Collection of code experiments in Julia. I'm doing this in Jupyter notebooks running the latest Julia kernel release (v. 1.0.0 at the time of the initial commit)

* `Bell Numbers.ipynb` - an implementation of Bell numbers. Illustrates high-precision calculations using BigFloat and BigInt types.
* `Bf.ipynb` - An implementation of brainfuck programming language in Julia
* `Shoelace Formula.ipynb` - an implementation of the shoelace formula for computing the area of a polygon.
* `KNN.ipynb` - an implementation of the K-Nearest Neighbors classifier. Techniques used: loading of delimited data, array manipulations through permutations, views.Also includes accuracy plot using Gadfly. I have used the MAGIC Gamma Telescope dataset (https://archive.ics.uci.edu/ml/datasets/magic+gamma+telescope), also included with the repo. The code will work with any numeric feature set, assuming the labels in the last column of the input CSV.

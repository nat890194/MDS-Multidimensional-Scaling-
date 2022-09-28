# MDS-Multidimensional-Scaling

- The multidimensional scaling approach minimizes the square difference of the pairwise distances between all the training data between the projected, lower dimensional, and original feature higher space.
- Metric Multidimensional Scaling : A generalization of classical multidimensional scaling with a variety of metrics and a loss function optimization. formulated as an optimization problem to minimize the squate difference between the original and projected pairwise distances
- $min_{x_1,\\ldots,x_m} \\sum_{i<j} \\left( ||x_i - x_j|| - \\delta_{i,j} \\right)^2\n$


    "\\begin{equation}\n",
    "min_{x_1,\\ldots,x_m} \\sum_{i<j} \\left( ||x_i - x_j|| - \\delta_{i,j} \\right)^2\n",
    "\\end{equation}\n",
    "\n",
    "where $||x_i - x_j||$ are the pairwise distances in the projected space ($p$ dimensional) and $\\delta_{i,j}$ are the pairwise distances in the original feature space.\n",
    "\n",
    "General comments about metric multidimensional scaling:\n",
    "\n",
    "* dissimilarity measure must be meaningful\n",
    "\n",
    "* dimensionality reduction is performed such that the error in the sample pairwise distance is minimized\n",
    "\n",
    "* there is a variant known as Nonmetric Multidimensional Scaling for ordinal features (categorical with ordering).\n",
    "\n"]
}

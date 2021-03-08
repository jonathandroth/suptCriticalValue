
# Computing Simultaneous Confidence Bands in R

Simultaneous confidence bands are versatile tools for visualizing estimation uncertainty for parameter vectors ([Montiel Olea and Plagborg-Møller 2019](https://onlinelibrary.wiley.com/doi/full/10.1002/jae.2656)). 

This repo houses a [R](https://www.r-project.org/) function that computes the critical values underlying the simultaneous sup-t confidence bands proposed in [Montiel Olea and Plagborg-Møller (2019)](https://onlinelibrary.wiley.com/doi/full/10.1002/jae.2656). 

## Example

[example.do](./example/code/example.do) shows how the simultaneous sup-t confidence bands can be estimated and plotted alongside their pointwise counterparts 

## Unit Tests

The repo houses two sets of unit tests:

* [basic_functionality.do](./test/code/basic_functionality.do) : This set asserts basic functionality
* [monte_carlo.do](./test/code/monte_carlo.do) : This set asserts expected coverage rates for a given data generating process 

Both sets of unit tests can be executed by running [make.py](./make.py).

## Author

Ryan Kessler
<br>Brown University
<br>Email: ryan.edmund.kessler@gmail.com

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details

## References

Montiel Olea, José Luis and Mikkel Plagborg-Møller. 2019. Simultaneous Confidence Bands: Theory, Implementation, and an Application to SVARs. Journal of Applied Econometrics. 

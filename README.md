# Simplification-of-multimodal-histogram

### This is an academic R&D code.
### The multimodal histogram is cut and approximated for each single peak so that the error is below an arbitrary threshold.
### For the algorithm, refer to the following paper.
### [Linear Time Algorithm for Approximating a Curve by a Single-Peaked Curve](https://link.springer.com/chapter/10.1007/978-3-540-24587-2_3)

# Use
## fitting_hist.py
### input  > file name, epsilon

ex.) Daily new infection of covid-19 in Japan
data from 厚生労働省　オープンデータ, https://www.mhlw.go.jp/stf/covid-19/open-data.html, access at 2021/04/20
![スクリーンショット (2)](https://user-images.githubusercontent.com/76963769/115184972-e4cfa580-a119-11eb-9ac0-d79ea74e914b.png)


### output > epsilon, num of peak, L2-norm, processing time and figure
ex.) Daily new infection of covid-19 in Japan
![スクリーンショット (3)](https://user-images.githubusercontent.com/76963769/115185003-f153fe00-a119-11eb-8663-e8b839f5ae02.png)


### please save the data as csv and work in the same directory.



## gaussian_fitting.ipynb
### This is a program that calculates the Gaussian approximation for each specified interval.
### Use the interval calculated in fitting_hist.py.

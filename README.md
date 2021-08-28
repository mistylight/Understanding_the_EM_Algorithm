# Understanding the EM Algorithm

Example codes for my blog post: [Understanding the EM Algorithm](https://mistylight.github.io/posts/20115/).

## Example 1: Two coins
Find the probabilities of two coins A and B, given 5 coin tossing trials with missing information:

| Trial ID | Coin    | Result     | \#heads / \#tails |
| -------- | ------- | ---------- | ----------------- |
| #1       | Unknown | HTTTHHTHTH | 5/5               |
| #2       | Unknown | HHHHTHHHHH | 9/1               |
| #3       | Unknown | HTHHHHHTHH | 8/2               |
| #4       | Unknown | HTHTTTHHTT | 4/6               |
| #5       | Unknown | THHHTHHHTH | 7/3               |

![Screen Shot 2021-08-23 at 12.16.15 AM](https://raw.githubusercontent.com/mistylight/picbed/main/Hexo/2021_08_23_ANpC4XhsQGvDRdL.png)

## Example 2: Girls and boys (GMM)
Infer the gender of 6 students given their heights (Note: in real life, inferring one's gender based on their height might be a bad idea. This example is for educational purposes only):

| Student ID | Gender  | Height (cm) |
| ---------- | ------- | ----------- |
| #1         | Unknown | 168         |
| #2         | Unknown | 180         |
| #3         | Unknown | 170         |
| #4         | Unknown | 172         |
| #5         | Unknown | 178         |
| #6         | Unknown | 176         |

![Screen Shot 2021-08-23 at 9.13.02 PM](https://raw.githubusercontent.com/mistylight/picbed/main/Hexo/2021_08_24_jspXEMbLyJvAogY.png)

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

[@mistylight](https://github.com/mistylight) - mistylight.cs@gmail.com

## Acknowledgements

[1] What is the expectation maximization algorithm? Chuong B Do, Serafim Batzoglou. Nature, 2008. [[paper](https://www.nature.com/articles/nbt1406.pdf)] 

[2] Expectation Maximization. Benjamin Bray. UMich EECS 545: Machine Learning course notes, 2016. [[course notes](https://github.com/thejakeyboy/umich-eecs545-lectures/blob/master/lecture16_clustering-mixtures-em/eecs545_expectation-maximization-notes.pdf)]

[3] The EM algorithm. Tengyu Ma, Andrew Ng. Stanford CS 229: Machine Learning course notes, 2019. [[course notes](http://cs229.stanford.edu/notes2020spring/cs229-notes8.pdf)]

[4] Bayesian networks: EM algorithm. Stanford CS 221: Artificial Intelligence: Principles and Techniques slides, 2021. [[slides](https://stanford-cs221.github.io/spring2021-extra/modules/bayesian-networks/em-algorithm.pdf)] 

[5] 如何感性地理解EM算法？工程师milter. 简书, 2017. [[blog post](https://www.jianshu.com/p/1121509ac1dc)]

[6] Coin Flipping and EM. Karl Rosaen, chansoo. UMich EECS 545: Machine Learning Materials. [[Jupyter Notebook](https://nbviewer.jupyter.org/github/eecs445-f16/umich-eecs445-f16/blob/master/handsOn_lecture17_clustering-mixtures-em/handsOn_lecture17_clustering-mixtures-em.ipynb#Problem:-implement-EM-for-Coin-Flips)]
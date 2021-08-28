# Understanding the EM Algorithm

Author: [@mistylight](https://github.com/mistylight)

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

## Example 2: Girls and boys (GMM)
Infer the gender of 6 students given their heights (Note: in real life, inferring one's gender based on their height can be a very bad idea. This example is for educational purposes only and is not meant to support the use of this method in practice):

| Student ID | Gender  | Height (cm) |
| ---------- | ------- | ----------- |
| #1         | Unknown | 168         |
| #2         | Unknown | 180         |
| #3         | Unknown | 170         |
| #4         | Unknown | 172         |
| #5         | Unknown | 178         |
| #6         | Unknown | 176         |
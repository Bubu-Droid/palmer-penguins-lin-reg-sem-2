# A Linear Regression on the Palmer Penguins Dataset

This was the project topic for my second semester statistics project.

- PDF: [main.pdf](main.pdf)
- TeX: [main.tex](main.tex)

## Project Abstract

This project studies the relationship between penguin body mass
and selected morphological traits using the Palmer Penguins
dataset. The response variable is body mass, while flipper
length, culmen length, culmen depth, and species are used as
predictors. Since biological measurements often follow
multiplicative scaling relationships, both the response and
the continuous predictors are log-transformed, yielding a
multiple log-linear regression model.

Species is incorporated through dummy variables, with Adelie
taken as the baseline category. The fitted model is estimated
using Ordinary Least Squares and explains a substantial
proportion of the variation in log body mass, with
$`R^2 = 0.8353`$ and adjusted $`R^2 = 0.8328`$. All predictors
except the intercept are statistically significant at the
$`5\%`$ level.

Confidence intervals, prediction intervals, and hypothesis
tests are constructed and interpreted. Residual diagnostics,
including plots, a normal Q-Q plot, and a chi-square
goodness-of-fit test, suggest that the assumptions of the
log-linear model are reasonably satisfied. The analysis shows
that penguin body mass is strongly associated with
morphological traits and species membership.

> [!NOTE]
> This abstract is AI generated,
> and so is the majority of the non-theoretical portion of this
> project, unlike my previous project which was handmade
> with love and care
> but received the same (if not less) marks than AI generated projects.
> I got 20 in this project and 19 in the previous one, just sad. ;-;

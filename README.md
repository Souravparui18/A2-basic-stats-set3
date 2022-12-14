# A2-basic-stats-set3
## Topics: Confidence Intervals
## 1.For each of the following statements, indicate whether it is True/False. If false, explain why.
### I. The sample size of the survey should at least be a fixed percentage of the population size in order to produce representative results.
Ans - False, The produce representative result it depends on the number of sample size(n) rather than percentage of the population size. A sample size of n>= 30 is considered a sufficiently large amount.

### II. The sampling frame is a list of every item that appears in a survey sample, including those that did not respond to questions.
True

### III. Larger surveys convey a more accurate impression of the population than smaller surveys.
True

## 2.PC Magazine asked all of its readers to participate in a survey of their satisfaction with different brands of electronics. In the 2004 survey, which was included in an issue of the magazine that year, more than 9000 readers rated the products on a scale from 1 to 10. The magazine reported that the average rating assigned by 225 readers to a Kodak compact digital camera was 7.5. For this product, identify the following:
### A) The Population
Ans - All of the PC Magazine Readers, only if we are interested in the readers of PC magazines, or else the population is all the users of different brands of electronics.

### B) The parameter of interest
Ans - population size, average, sample size and ratings scale (7.5 for Kodak Camera).

### C) The sampling frame
Ans - Every reader that responded by rating the products(9000 readers).

### D) The sample size
Ans - 225 readers.

### E) The sampling design
Ans - Voluntary Response

### F) Any potential sources of bias or other problems with the survey or sample
Ans- The key to random selection is that is not biased in the selection of the sample, but surveys conducted by the magazines often suffer from nonresponse bias and also the source of this data is from readers that read PC magazine vs the whole population that do not read PC magazine yet they use these different brands of electronics.

## 3.For each of the following statements, indicate whether it is True/False. If false, explain why.
### I. If the 95% confidence interval for the average purchase of customers at a department store is 50𝑡𝑜 110, then $100 is a plausible value for the population mean at this level of confidence.
Ans - True

### II. If the 95% confidence interval for the number of moviegoers who purchase concessions is 30% to 45%, this means that fewer than half of all movie goers purchase concessions.
Ans - True

### III. The 95% Confidence-Interval for μ only applies if the sample data are nearly normally distributed.
Ans - False: The 95% confidence Interval for population mean can be applied to distribution that aren’t normal, but they are easy to understand in symmetric distributions. We can use the central limit theorem to make a normal approximation. The rule where about 95% of observations are within 2 standard deviations of the mean is only approximately true. However, it holds very well for the normal distribution. The mean of data tends to be normally distributed when the sample size is sufficiently large.

## 4.What are the chances that X_bar > mu ?
### A)¼ B)½ C)¾ D)1
Ans B - This is only an assumption, because if we consider more than 50% for sample than there is a higher probability of having sample mean will be greater than population mean.

## 5.In January 2005, a company that monitors Internet traffic (WebSideStory) reported that its sampling revealed that the Mozilla Firefox browser launched in 2004 had grabbed a 4.6% share of the market.
### I.If the sample were based on 2,000 users, could Microsoft conclude that Mozilla has a less than 5% share of the market?
Ans - False, As the p Value > alpha for 95% confidence we failed to reject null hypothesis Ho: > 5% null hypothesis

### II. WebSideStory claims that its sample includes all the daily Internet users. If that’s the case, then can Microsoft conclude that Mozilla has a less than 5% share of the market?
Ans - True

## 6.A book publisher monitors the size of shipments of its textbooks to university bookstores. For a sample of texts used at various schools, the 95% confidence interval for the size of the shipment was 250 ± 45 books. Which, if any, of the following interpretations of this interval are correct?
### A. All shipments are between 205 and 295 books.
Ans - False, 95% of the time the size of the shipment will be around 250 +/- 45 books.

### B. 95% of shipments are between 205 and 295 books.
Ans - True

### C. The procedure that produced this interval generates ranges that hold the population mean for 95% of samples.
Ans - True

### D. If we get another sample, then we can be 95% sure that the mean of this second sample is between 205 and 295.
Ans - True

### E. We can be 95% confident that the range 160 to 340 holds the population mean.
Ans - False, As we increase the range +/- 1 sigma the % of confidence increases for a normal distribution it will be 97.5% that the mean will lie in between 160 to 340 (-3 sigma to +3 sigma)

## 7.Which is shorter: a 95% z-interval or a 95% t-interval for μ if we know that σ =s?
A. The z-interval is shorter B. The t-interval is shorter C. Both are equal D. We cannot say
Ans A - For 95% confident Z-interval is shorter (1.960), as for t-interval (1.962) it increases as degree of freedom decreases.

## Questions 8 and 9 are based on the following: To prepare a report on the economy, analysts need to estimate the percentage of businesses that plan to hire additional employees in the next 60 days.
## 8.How many randomly selected employers (minimum number) must we contact in order to guarantee a margin of error of no more than 4% (at 95% confidence)?
A)600 B)400 C)550 D)1000
Ans - Margin of Error = Z * under root ((p*(1-p))/n) where Z = z-value for your selected confidence interval, p = it is the sample proportion, n = is the sample size

let's assume p value as 0.5 and margin of error(me) is given by 0.04

therefore n = Z^2 * ((p*(1-p))/me^2) = (1.96)^2 * ((0.5*(1-0.5))/(0.04)^2) = 600 sample size

## 9.Suppose we want the above margin of error to be based on a 98% confidence level. What sample size (minimum) must we now use?
A)1000 B)757 C)848 D)543

Ans: C Let’s assume p hat and q hat as 0.5 and margin of error is given 0.04 n = (z)^2 * p hat * q hat / ME ^2 n = (2.32) ^2 * (0.5) (0.5) / (0.04) ^2 = 841 samples size

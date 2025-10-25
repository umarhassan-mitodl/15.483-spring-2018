---
content_type: page
description: This section outlines the details of the assignment.
learning_resource_types:
- Assignments
ocw_type: CourseSection
parent_title: Assignments
parent_type: CourseSection
parent_uid: 36cef9a4-d20e-0eb9-074b-f156d59b4dc2
title: Assignment 4
uid: b4171b45-c636-a7e1-1bea-17504d6a2cfd
---

This is an individual assignment.

Assignment 4: Consumer Credit Provision and the Credit Card Market
------------------------------------------------------------------

You may solve this assignment numerically, using a software of your choice (e.g., excel, matlab), or analytically. The point of the problem is not the numeric answers, but rather the understanding of how borrower behavior, lender competition, and regulation interact. That written, this problem captures almost the essence of the complex problems that lenders consider when setting interest rates and competing with other credit providers, as well as how debt-backed securities are priced. In other words, this is a problem that, at a high-level, is the sort that executives handle at lending companies, both established (like credit card providers) and innovating (like peer to peer lenders and those pricing the securities derived from these loans).

“Better Tomorrow” (BT) is a credit card company which specializes in lending to people who are down on their luck over two months denoted \\( t = \\lbrace 1, 2 \\rbrace \\) . The market is very competitive so BT prices their loans (interest rate) at their cost of funds (or hurdle rate, or required rate of return).

BT’s customers want to borrow so they may consume in period 1 (denoted \\( C\_1 \\) ) and period 2 (denoted \\( C\_2 \\) ). BT’s customers have no income this month ( \\( Y\_1 = 0 \\) ) so they borrow some amount B1 in order to make ends meet. Assume they have no other loans or assets to draw on so their consumption in period 1 corresponds to the amount they borrow ( \\( C\_1 = B\_1 \\) ). Consumers have diminishing returns from consumption so their utility is concave and given by \\( U(C\_1 , C\_2) = C\_1 + C\_2 \\) . As rational agents their objective is to determine \\( C\_1 \\) and \\( C\_2 \\) that maximize their expected utility, ultimately pinning down \\( B\_1 \\) in the process.

Answer the following questions:

### 1\. Warm-up

Suppose all consumers will have income \\( Y\_2 = $1000 \\) in the second month. BT asks for a lump-sum repayment of \\( (1+r)B\_1 \\) (\\( r \\) is the interest rate) next month from anyone who borrows \\( B\_1 \\) this month. What value of \\( r \\) would result in zero excess proﬁts for BT if the monthly cost of funds is 1%? If BT charges this value of \\( r \\), what will its customers choose for \\( B\_1 \\)?

Warm-up solution:

*   Each borrower pays \\( (1 + r)B\_1 \\) in month \\( t = 2 \\).
*   BT has a cost of funding of 1% so the cost of these funds is \\( (1 + 0.01)B\_1 \\).
*   Proﬁts (π) correspond to the difference which is given by  
      
    \\( \\eqalign π = (1 + r)B\_1 − (1 + 0.01)B\_1 \\)  
      
    As a result, the most competitive interest rate that BT can offer is the one that sets payment equal \\( r = 1% \\), which makes zero excess proﬁts \\( (π = 0) \\).
*   A borrower who consumes \\( C\_1 \\) will also consume \\( C\_2 = Y\_2 − (1 + 0.01)C\_1 \\).
*   So they should choose \\( C\_1 \\) to maximize \\( \\sqrt C\_1 + \\sqrt C\_2 = \\sqrt C\_1 + \\sqrt Y\_2 - (1 + 0.01 ) C\_1 \\). The borrower is best off with \\( C\_1 = B\_1 = $493 \\).

### 2\. Setting rates with default risk

Now suppose BT’s cost of funds is zero - it is 2010 after all and the Fed has ﬂooded the market with liquidity so the Federal Funds rate is effectively zero. However, in 2010, times are also bad and every cus-tomer has a 20% chance having \\( Y\_2 = 0 \\) next month, and an 80% chance of having \\( Y\_2 = 1000 \\). Customers with \\( Y\_2 = 1000 \\) will repay \\( (1 + r)B\_1 \\) to BT (as in part 1), but customers with Y1 = 0 will repay nothing. (Note, customers who default on their loan also have C2 = 0). In this case, what value of \\( r \\) would result in zero excess proﬁts for BT? If BT charges this value of r, what will its customers choose for \\( B\_1 \\)? Does your answer change if consumers are overoptimistic, and believe the chances of \\( Y\_2 = 1000 \\) are 100%?

Hints:

*   The cost of funds is zero but the bank only gets paid 80% of the time. The interest rate r that results in zero excess proﬁts needs to compensate the bank for the possibility of a default.
*   The borrower knows that he will not consume, and consequently default, when he receives \\( Y\_2 = 0 \\). His expected utility needs to account for the possibility of not consuming in period 2.
*   If the borrower is overoptimistic then he will no longer consider the possibility of not consuming in month 2. However, the bank will and it still charges the same r that accounts for the possibility of a default.

### 3\. Setting rates with information about different default risks

Suppose that the overall default rate is still 20%, but half of BT’s customers are “prime” and have a 0% chance of \\( Y\_2 = 0 \\), while the other half are “subprime” and have a 40% chance of \\( Y\_2 = 0 \\). If BT can observe a credit score that reveals who is prime and who is subprime, what would be BT’s zero-proﬁt interest rate in the prime and subprime market? Are subprime borrowers made better or worse off by the availability of credit scores? Are prime borrowers? Does this conclusion seem consistent with consumer advocacy, regulations or the supposed beneﬁts of using more information in lending?

Hints:

*   The bank is capable of establishing two separate rates since it can rely on a credit score to perfectly identify each type of borrower. The logic is the same as before, the only difference is in the percentage of default associated to each type of borrower.

### 4\. Setting rates and then disregarding new information about different default risks

Suppose that before the ﬁrst month, consumers don’t know yet if they will be prime or subprime (and nor does BT). Everyone has a 50% chance of ending up as a subprime customer, and a 50% chance of ending up as a prime customer. BT could then offer consumers a card priced as in problem 2 before month 1, and could commit not to use credit scores to price differently to prime and subprime borrowers once this became clear at the start of month 1 when the consumers are looking to borrow. Would consumers like this card or prefer to have BT reset the rate after their creditworthiness is revealed? While BT might commit, what would BT’s competitors do once it was clear who was prime and subprime? (This is the essence of how consumer insurance markets can unravel.)

Hints:

*   The borrowers can either obtained a pooled rate where the bank cannot dis-tinguish their type, or face a 50/50 “gamble” where they end up as prime/sub-prime. All of these rates were computed in the previous lines.
*   Risk averse agents (concave utility function) dislike gambling and prefer to obtain an average of the interest rates rather than gambling 50/50 with a low and high rate.

### 5\. Reality

In 2007, Citi started a credit card campaign, “A Deal is a Deal&mdash;as long as the cardholder upholds her end of the card’s terms, Citi will not reprice her card more than once every 2 years” (See this article on [Citigroup](http://www.nytimes.com/2008/06/25/business/media/25adco.html?_r=0)). The campaign was a ﬂop in many ways. Few people took the card up and Citi ended up losing money on the cards issued. Given your answer to question 4, why do you think the campaign was a ﬂop? Is there a behavioral economics explanation? An adverse selection explanation? A competitive “poaching” explanation?
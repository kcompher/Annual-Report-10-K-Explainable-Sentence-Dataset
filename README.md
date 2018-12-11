# Annual Report(10-K) Explainable Sentence Dataset

## Explainable Sentence Dataset Description

Explainable Sentence Dataset contains ~160,000 sentences (extracted from 'Management's Discussion & Analysis' of Annual Reports (1996-2018)). Sentences from this dataset provide reasons for changes in the company's stock price.

### Sample data

>[0001574910-10-K-20160413.txt]<br />
  The increase in operating expense was primarily attributed to an increase in professional fees during fiscal 2015 resulting from our acquisition of various subsidiaries, our change in year end, the change in our control, and the various audit and reporting requirements associated with those activities.<br />
  The increase was due to cash received from financing activities during the 2015 that were not entirely spent.<br />
  The increase was due to cash received from financing activities during the 2015 that were not entirely spent.<br />
  The decrease in total liabilities was attributed to a reduction of notes payable to related and non-related parties.<br />
  The increase in our working capital deficit was due to an increase in accrued expenses and an increase in related party loans during fiscal 2015.<br />
  The increase in our working capital deficit was due to an increase in accrued expenses and an increase in related party loans during fiscal 2015.<br />
  The decrease in cash used for operating activities was due to the fact that our company was limited to available cash on hand and amounts received from financing activities to repay outstanding operating activities during the year.<br />
  The decrease in cash used for operating activities was due to the fact that our company was limited to available cash on hand and amounts received from financing activities to repay outstanding operating activities during the year.<br />
  The increase in cash provided by financing activities is due to more proceeds from related parties.<br />
  The increase in cash provided by financing activities is due to more proceeds from related parties.


### Preprocessing
1. Extract "Management's Discussion & Analysis' from Annual Report.
2. Extract explainable sentences from 1.

### Dataset Reference
'Management's Discussion & Analysis' of Annual Reports(1996-2006) http://www.cs.cmu.edu/~ark/10K/
These data were primarily by Bryan Routledge, Shimon Kogan, Jacob Sagi, and Noah Smith.
 
### Preprocessing Reference
We followed the MDA extraction method from the paper ["Predicting Risk from Financial Reports with Regression"](https://homes.cs.washington.edu/~nasmith/papers/kogan+levin+routledge+sagi+smith.naacl09.pdf)

## Download
If you want to download dataset please email to yeeun@unist.ac.kr

## Acknowledgement

<img src="http://xai.unist.ac.kr/static/img/logos/XAIC_logo.png" width="300" height="100">

### **Project Name**
> A machine learning and statistical inference framework for explainable artificial intelligence(의사결정 이유를 설명할 수 있는 인간 수준의 학습·추론 프레임워크 개발)

### **Managed by**
> Ministry of Science and ICT/XAIC

### **Participated Affiliation**
> UNIST, Korea Univ., Yonsei Univ., KAIST., AItrics

### **Web Site**
> <http://openXai.org>

### LICENSE
> This data is made available under the Creative [Commons CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/legalcode).

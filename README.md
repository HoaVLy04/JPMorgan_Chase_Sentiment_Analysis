# JPMorgan Chase Customer Sentiment Analysis

# Hoa Ly

## Description
This project analyzes the customer narrative complaint from JP Morgan Chase to find relationship between customer's emotion with complaint dispute rate. In this project, I compare the emotional content of disputed vs. non-disputed complaints to identify emotional patterns that might predict complaint resolution difficulty.

## Data Dictionary 📖
Our dataset includes the following columns:

- **Date.received**: Date that the complaint was received
- **Product**: Product that was complaint about (i.e Debt Collection, Mortgage,..)
- **Sub.product**: Sub category of the product (i.e Credit Card, Debit Card,...)
- **Issue**: Issue category
- **Sub.issue**: Sub issue category
- **Consumer.complaint.narrative**: Consumer explanation on the issue
- **Company.public.response**: Company public response via website or social media
- **Company**: Name of bank. Note: Our dataset includes all US banks, but for the range of this project I will filter out only JP Morgan Chase Co.
- **State**: State where the headquarter is located
- **ZIP.code**: ZIP code where the headquarter is located
- **Tags**: The department/office that the issue will be directed to 
- **Consumer.consent.provided.**: Consumer consent to public issue
- **Submitted.via**: Platform the issue was submitted
- **Date.sent.to.company**: Date that the issue was sent to the bank
- **Company.response.to.consumer**: Company resolution to the issue
- **Timely.response**: Whether if this is a timely response or not
- **Consumer.disputed.**: Whether if the consumer dispute the resolution or not
- **Complaint.ID**: The unique identifier of each complaint

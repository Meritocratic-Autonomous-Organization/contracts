# Token Request

1Hive's Token Request app allows users to create a vote which requests an Organization's tokens in exchange for payment. For example a user may request minting 100 organization tokens in exchange for 100 DAI. The request would require a vote to approve, if the vote is rejected the user would receive their payment back and if it is approved the payment would be deposited in the organization's vault.

#### 🚨 Security review status: [Contracts audited](https://diligence.consensys.net/audits/2019/12/dandelion-organizations/)

# Token Request Vesting

The same app with added vesting functionality. Tokens received by the user will be vested for a period of time specified by the contract manager.

start - The date vesting started
cliff - The cliff period
end - The fully vested date

You will receive your tokens right after generating in our DAO. Cliff means the period of time after which the first portion of your tokens will become transferable. Vesting means the period of time after which all your tokens will become transferable.

![image](https://user-images.githubusercontent.com/111743010/229352779-46ae6731-e371-4605-9468-fedd65632d68.png)

# Loan-activity-using-Blockchain

Loan Sanction Smart Contract

This repository houses a robust Solidity smart contract that implements a comprehensive loan sanction system. Built on the Ethereum blockchain, this contract empowers lenders with the ability to efficiently approve or reject loan requests made by borrowers. By leveraging the transparency and immutability of blockchain technology, the contract ensures a secure and auditable process.

The contract encompasses essential features for loan management. Borrowers can initiate a loan request by specifying the desired loan amount, kicking off the process. Once a loan request is made, the lender can carefully evaluate and decide to either approve or reject it based on predetermined criteria. This streamlined approval process provides lenders with control and flexibility in managing their loan portfolio.

Furthermore, the smart contract handles loan repayment in a seamless manner. Borrowers are given a specific deadline within which they can repay the loan amount. The contract calculates the repayment amount, including the principal loan amount as well as any interest accrued based on the interest rate established by the lender. This automated interest calculation ensures accurate and fair repayment terms for borrowers.

To complete the process, the contract enables the lender to withdraw funds after the repayment deadline has passed. This withdrawal functionality grants lenders access to their funds once the loan terms have been fulfilled, ensuring a smooth and convenient experience.

By utilizing the power of blockchain and Solidity, this loan sanction system offers transparency, security, and efficiency for both lenders and borrowers. It streamlines the loan management process, mitigates risks, and provides a trustworthy environment for financial transactions. Whether you are a developer, researcher, or industry professional, this smart contract serves as a solid foundation for building advanced loan sanction systems on the blockchain.

Features
<ul style="list-style-type: disc; padding-left: 20px;">
  <li style="margin-bottom: 10px;">Loan request: Borrowers can request a loan by specifying the loan amount.</li>
  <li style="margin-bottom: 10px;">Loan approval: The lender can approve or reject the loan request.</li>
  <li style="margin-bottom: 10px;">Loan repayment: Borrowers can repay the loan amount within the specified deadline.</li>
  <li style="margin-bottom: 10px;">Interest calculation: The repayment amount includes the loan amount plus the interest calculated based on the interest rate set by the lender.</li>
  <li style="margin-bottom: 10px;">Withdrawal: The lender can withdraw the funds after the repayment deadline has passed.</li>
</ul>
<br>
Getting Started
To use or contribute to this project, follow the steps below:

Clone the repository:<br>
`git clone https://github.com/bysani2003/loan-activity-using-Blockchain.git`<br>
Install dependencies:<br>
`cd loan-sanction-smart-contract
npm install`<br>
Compile the smart contract:<br>
`npx truffle compile`<br>
Run the tests:<br>
`npx truffle test`<br>
Deploy the smart contract on a test network or a local blockchain:<br>
`npx truffle migrate`

wasquery_id: 1794014953609
amount: "533500"
destination: 0:59baccfe6657703f73611d978a02abd1ea4c2631cf1ec5eeb825b5157b2ae129
response_destination: 0:2d08d27e0ca64ece6011c3cee1602bd85de9f0595883efbc75f52298d02cd064
custom_payload: null
forward_ton_amount: "1000000"
forward_payload:
  is_right: true
  value:
    sum_type: TextComment
    op_code: 0
    value:
      text: paidz:withdraw:cmw5pt4nm00o0o1017e8xmksq# Open Auction Program
Enables simple decentralized auctions, which accepts bids and transfers the winning bid to the pre-specified beneficiary. Built on the Solana network.

## How does it work?
- Anyone can initialize an auction with a specified begin and end time
- Anyone can bid in the auction within the specified times. Auctions currently accept the SOL token
- After the auction end time passes, anyone can trigger the transfer of the winning bid to the beneficiary. All unsuccessful bidders can also receive a refund.

## Next Steps
- Allow the prize of the auction to be an SPL token or NFT, held by the auction program
- Support bidding via any SPL token

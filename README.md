# standard-barcodeverified

> “Barcode verified” is an open specification, version 0.1, formally titled “AI Product Match Verification”. It defines what a verified product match is, what evidence it rests on, and what a receipt for one must carry. Any artificial intelligence (AI), retailer or brand may implement it; the words “Barcode verified” are free to any conforming implementation. It answers one question for an AI agent at the moment of purchase: is the product the shopper asked for, the product the merchant is offering, and the product on the verified record, all the same barcode — and how does the agent prove it checked.

Built and run by [wefetch](https://wefetch.ai/). This is the public connect kit, MIT. It holds no deploy code and no keys.

## Connect

This surface publishes for agents; it has no tool endpoint of its own.

- For agents: https://standard-barcodeverified.org/llms.txt
- Agent card: `https://standard-barcodeverified.org/.well-known/agent-card.json` (copy in this repo, `agent-card.json`)
- Site: https://standard-barcodeverified.org/

```bash
curl https://standard-barcodeverified.org/llms.txt
```

Artificial intelligence makes mistakes. Check what matters.

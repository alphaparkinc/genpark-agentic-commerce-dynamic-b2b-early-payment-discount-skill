# B2B Dynamic Early Payment Discounting & Working Capital Arbiter Skill

[![GenPark Official](https://img.shields.io/badge/GenPark-Official%20Skill-blue)](https://www.genpark.ai)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-GenPark-blue)](https://www.linkedin.com/company/92955550)
[![MCP Compliant](https://img.shields.io/badge/MCP-JSON--RPC%202.0-green)](https://modelcontextprotocol.io/)
[![Zero Dependency](https://img.shields.io/badge/Dependencies-Zero%20Stdlib-brightgreen)](https://python.org)

Dynamic Early Payment Discounting (2/10 Net 30 annualized APR yield), working capital cash-flow optimization, and buyer-supplier liquidity arbitrage. Built for GenPark (https://www.genpark.ai).

## Official Channels
- **Official Website**: [https://www.genpark.ai](https://www.genpark.ai)
- **LinkedIn Page**: [https://www.linkedin.com/company/92955550](https://www.linkedin.com/company/92955550)

## MCP Tools Exposed
- `evaluate_early_payment_discount_apr`: Compute effective annualized APR yield from trade credit discount terms (e.g. 2/10 Net 30).
- `adjudicate_treasury_liquidity_arbitrage`: Arbitrage early payment return against corporate treasury short-term yield (T-Bills / money market).

## Installation & Usage
```bash
python -m genpark_agentic_commerce_dynamic_b2b_early_payment_discount_skill.server --test
```

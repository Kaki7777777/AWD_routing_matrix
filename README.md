# AWD Routing Decision Matrix

A comprehensive decision framework for Amazon Warehouse and Distribution (AWD) routing optimization.

## 🎯 Overview

This tool helps determine optimal routing paths through AWD nodes based on:
- **Velocity Tiers**: HEAD/BODY/TAIL classification
- **Product Characteristics**: SKU complexity, seasonality, size, value, regional requirements
- **Seller Strategies**: Arbitrage, test-and-learn, established patterns

## 📊 Live Demo

View the interactive decision matrix: [AWD Routing Matrix](https://your-username.github.io/awd-routing-matrix/)

## 🏗️ AWD Network Structure

### Origin AWD DC
- **Shenzhen**: Primary intake point for international inventory

### Destination AWD DCs
- US West Coast
- US East Coast  
- US Middle
- UK
- DE

## 🎯 Key Decision Points

### When to Use Origin AWD
- TAIL velocity + SKU-Heavy products
- Arbitrage/Multi-market sellers
- Uncertain demand patterns
- Cross-border compliance needs

### When to Go Direct to AFN
- Ultra-fast velocity + predictable demand
- Time-sensitive products
- Single FC destinations
- High handling sensitivity

## 📋 Validated Use Cases

- **SKU-Heavy BODY/TAIL**: B&K Fashion
- **Seasonal HEAD/BODY/TAIL**: REDESS  
- **Seasonal BODY/TAIL**: Joyspot, Transy

## 🚀 Usage

1. Classify product velocity (HEAD/BODY/TAIL)
2. Identify product characteristics
3. Determine seller strategy type
4. Apply routing decision matrix
5. Execute optimized AWD route

## 📁 Repository Structure

```
docs/
├── index.html          # Main decision matrix
└── README.md          # This file
```

## 🤝 Contributing

This framework is based on real seller use cases and AWD network analysis. Contributions and feedback welcome.

## 📄 License

MIT License - see repository for details.

# Inventory Flow Optimizer

A sophisticated inventory management calculator for optimizing supply chain flow and maintaining target Days on Hand (DOH).

## Features

- **Multi-location inventory tracking**: FBA, US 3PL, CN 3PL, In Transit, and WIP
- **Dynamic production planning**: Automatically calculates optimal production quantities
- **Smart shipping decisions**: Prioritizes US inventory for urgent needs, CN for long-term supply
- **Sales forecasting**: Supports both growth rate and monthly forecast modes
- **Visual analytics**: Interactive charts and supply chain visualization
- **Event tracking**: Unique IDs for shipments and production orders

## Live Demo

Visit the live application: [Inventory Flow Optimizer](https://[your-username].github.io/inventory-flow-optimizer/)

## Usage

1. Set your initial inventory levels across all locations
2. Configure lead times and production parameters
3. Choose between growth rate or monthly sales forecast
4. Run the simulation to see optimized inventory flow
5. Use the slider to explore inventory levels at any point in time

## Key Metrics

- **Target DOH**: 60 days (customizable)
- **DOH Tolerance**: ±10% (54-66 days optimal range)
- **Minimum shipment sizes**: Configurable per location
- **Production and shipping lead times**: Fully customizable

## Technology

- Pure HTML/CSS/JavaScript - no dependencies except Chart.js
- Client-side only - no backend required
- Responsive design for desktop and tablet use

## License

MIT License
# Game Vehicle Analysis & Recommendation System

An analytical system for evaluating in-game vehicle pricing and providing personalized recommendations using machine learning techniques.

## Overview

This project implements a data-driven approach to:
- Analyze reasonableness of in-game vehicle pricing
- Reduce dimensionality using PCA and scaling
- Provide vehicle recommendations using BallTree nearest neighbor search
- Compare different ML models for price prediction

## Key Features

- Vehicle price prediction using multiple models (Linear Regression, Random Forest, CNN)
- Feature importance analysis for pricing strategy optimization
- Separate analysis for different vehicle classes (cars, military vehicles, planes)
- Nearest neighbor recommendation system using BallTree algorithm

## Technical Implementation

### Data Processing
- Feature scaling and normalization
- PCA implementation for dimensionality reduction
- Vehicle class separation for improved model performance

### Models
- Linear Regression (baseline)
- Random Forest (best performing)
- CNN (comparative analysis)

### Performance Metrics
- Random Forest: R² improved from 0.51 to 0.65 after class separation
- Key pricing features identified: acquisition method, acceleration, handling, top speed, vehicle class

## Applications

1. Price Reasonableness Evaluation
   - Feature weight adjustment
   - Price prediction for new vehicles
   - Market balance analysis

2. Player-Focused Systems
   - Customized item creation
   - In-game trading system support
   - Personalized vehicle recommendations

3. Dynamic Pricing Strategy
   - Class-based pricing patterns
   - Feature importance-based price adjustments
   - Market dynamics integration

## Results

The analysis revealed:
- Nonlinear relationships between features and prices
- Distinct pricing patterns across vehicle classes
- Improved prediction accuracy with class separation
- Military vehicles share pricing patterns with cars more than planes

## Future Improvements

- Integration with player feedback systems
- Real-time price adjustment mechanisms
- Enhanced recommendation algorithms
- Market dynamics simulation

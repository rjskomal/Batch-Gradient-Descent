prediction = weight × x + bias

MSE = (1/M) × Σ (predicted − actual)²

weight = weight − learning_rate × ∂Loss/∂weight

bias   = bias   − learning_rate × ∂Loss/∂bias

∂Loss/∂weight = (2/M) × Σ (predicted − actual) × x

∂Loss/∂bias   = (2/M) × Σ (predicted − actual)

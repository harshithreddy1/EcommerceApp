### `QUALITY-GATE.md`  

```markdown
# QUALITY-GATE.md

## Custom SonarQube Quality Gate for EcommerceApp

**Gate Conditions:**
- **Duplicated Lines Density:** ≤ 6%  
- **Maintainability Rating:** ≥ B  
- **Cognitive Complexity:** fail if any file > 15 (proxy for readability)

### Justification:

1. **Duplicated Lines Density ≤ 6%**
   - Controls code duplication and improves maintainability.

2. **Maintainability Rating ≥ B**
   - Ensures overall code quality for the e-commerce application.

3. **Cognitive Complexity Threshold**
   - Acts as a proxy for readability and maintainability; files with high complexity should be refactored.

### Notes:
- This Quality Gate will **fail the Jenkins pipeline** if thresholds are violated.  
- Helps maintain high-quality, readable, and maintainable code.  

### Screenshots:
- Include SonarQube screenshots showing the custom Quality Gate configuration.  
- Include example Sonar analysis screenshots after pipeline execution.


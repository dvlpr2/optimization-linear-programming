
# Optimization with Linear Programming

This notebook shows how to solve 2 optimization problems with LP (Linear Progrmming)

### 1st Problem : LP with real decision variables

    max (m1*x1 + m2*x2 + m3*x3 + m4*x4)

    subject to :
     * [1 1 1 1] . [x1 x2 x3 x4] = 10,000,000.00
     * x1 + x3 <= 6,000,000.00
     * 4*x1 + 2*x2 + 2*x3 + x1 <= 20,000,000.00
     * x1 <= 4,000,000.00
     * x4 <= 4,000,000.00
     * x4 <= 4,000,000.00
     * x4 <= 4,000,000.00

### 2nd Problem : LP with binary decision variables

    max (b1*x1 + ... + b8*x8)

    subject to :
     * c1*x1 + ... c8*x8 <= C
     * x1, ... , x8 : binary


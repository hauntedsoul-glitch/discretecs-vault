
aliases: [Summation Notation, Summation] tags: [math/discrete, notation, sequences] created: 2026-01-26 updated: 2026-01-26

## Definition

> [!tldr] Definition
> 
> **Sigma notation** (or summation notation) is a concise way to represent the sum of a sequence of numbers. It uses the Greek capital letter $\Sigma$ (sigma) to denote that multiple terms are being added together.

A typical expression looks like this:

$$\sum_{i=m}^{n} a_i$$

- **$i$**: The **index of summation** (a variable that changes).
    
- **$m$**: The **lower limit** (the starting integer).
    
- **$n$**: The **upper limit** (the stopping integer).
    
- **$a_i$**: The **general term** or formula applied to each index value.
    

## Examples and Non-Examples

### Examples

- **Arithmetic Sum**: $\sum_{i=1}^{4} i = 1 + 2 + 3 + 4 = 10$
    
- **Squares**: $\sum_{k=0}^{3} k^2 = 0^2 + 1^2 + 2^2 + 3^2 = 14$
    
- **Constant**: $\sum_{i=1}^{5} 10 = 10 + 10 + 10 + 10 + 10 = 50$
    

### Non-Examples

- **$a_1 + a_2 + a_3 + \dots$**: This is an infinite series. While it can be written as $\sum_{i=1}^{\infty} a_i$, a simple list of terms without the $\Sigma$ operator is just the expansion, not the notation itself.
    
- **$\prod_{i=1}^{n} a_i$**: This is **Pi notation**, which represents the _product_ (multiplication) of terms, not the sum.
    

## Resources

<iframe width="560" height="315" src="https://www.google.com/search?q=https://www.youtube.com/embed/S9enR8Zp780" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Other resources:

- [Khan Academy: Sigma Notation Basis](https://www.google.com/search?q=https://www.khanacademy.org/math/algebra2/x2ec2f6f830c9fb89:sequences/x2ec2f6f830c9fb89:sig-not/v/sigma-notation-basic)
    
- [Wolfram MathWorld: Summation](https://mathworld.wolfram.com/Summation.html)
    

## Practice

1. **Evaluate**: $\sum_{j=2}^{5} (2j - 1)$
    
    - _Solution_: $(2(2)-1) + (2(3)-1) + (2(4)-1) + (2(5)-1) = 3 + 5 + 7 + 9 = 24$.
        
2. **Rewrite in Sigma Notation**: $1 + 4 + 9 + 16 + 25$
    
    - _Solution_: $\sum_{i=1}^{5} i^2$
        
3. **Property Check**: True or False? $\sum_{i=1}^{n} c \cdot a_i = c \cdot \sum_{i=1}^{n} a_i$
    
    - _Solution_: True (Distributive Property).
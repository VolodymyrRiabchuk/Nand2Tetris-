# Boolean Algebra 

## Values

Values of the variables are the truth values **true** and **false** (usually called boolean type in programming), usually denoted 1 and 0.

## Operations
### Conjunction: 

    Logic operator: AND

    Algebraic operator: ∧

    Truth table for conjunction operation AND:  

    | *x* | *y* | *x* AND *y* |
    |:---:|:---:|:---:|
    | 0 | 0 | 0 |
    | 0 | 1 | 0 |
    | 1 | 0 | 0 |
    | 1 | 1 | 1 |

### Disjunction: 

    Logic operator: OR

    Algebraic operator: ∨

    Truth table for disjunction operation OR: 

    | *x* | *y* | *x* OR *y* |
    |:---:|:---:|:---:|
    | 0 | 0 | 0 |
    | 0 | 1 | 1 |
    | 1 | 0 | 1 |
    | 1 | 1 | 1 |

### Negation: 

    Logic operator: NOT

    Algebraic operator: ¬

    Truth table for negation operation NOT: 

    | *x* | NOT( *x* ) |
    |:---:|:---:|
    | 0 | 1 |
    | 1 | 0 |

## Laws

### Monotone Laws:

* Associativity of disjunction operation OR (∨): 
> *x* ∨ ( *y* ∨ *z* ) = ( *x* ∨ *y* ) ∨ *z* 

> x OR ( y OR z ) = ( x OR y ) OR z 

* Associativity of conjunction operation AND (∧):
> *x* ∧ ( *y* ∧ *z* ) = ( *x* ∧ *y* ) ∧ *z* 

> x AND ( y AND z ) = ( x AND y ) AND z 

* Commutativity of disjunction operation OR (∨):
> *x* ∨ *y* = *y* ∨ *x* 

> x OR y = y OR x  

* Commutativity of conjunction operation AND (∧):
> *x* ∧ *y* = *y* ∧ *x* 

> x AND y = y AND x 

* Distributivity of conjunction operation AND (∧) over disjunction operation OR (∨):

> *x* ∨ ( *y* ∧ *z* ) = ( *x* ∨ *y* ) ∧ ( *x* ∨ *z* )

> x OR ( y AND z ) = ( x OR y ) AND ( x OR z )

* Distributivity of disjunction operation OR (∨) over conjunction operation AND (∧):

> *x* ∧ ( *y* ∨ *z* ) = ( *x* ∧ *y* ) ∨ ( *x* ∧ *z* )

> x AND ( y OR z ) = ( x AND y ) OR ( x AND z )

* Identity for disjunction operation OR (∨):

> *x* ∨ 0 = *x*

> x OR 0 = x

* Identity for conjucntion operation AND (∧):

> *x* ∧ 1 = *x*

> x AND 1 = x

* Annihilator for conjucntion operation AND (∧):

> *x* ∧ 0 = 0

> x AND 0 = 0

* Annihilator for disjunction operation OR (∨):

> *x* ∨ 1 = 1

> x OR 1 = 1

* Idempotence of disjunction operation OR (∨):

> *x* ∨ *x* = *x*

> x OR x = x

* Idempotence of conjucntion operation AND (∧):

> *x* ∧ *x* = *x*

> x AND x = x

* Absorption 1:

> *x* ∧ ( *x* ∨ *y* ) = *x*

> x AND ( x OR y ) = x

* Absorption 2:

> *x* ∨ ( *x* ∧ *y* ) = *x*

> x OR ( x AND y ) = x

### Nonmonotone Laws:

* Complementation 1:

> *x* ∧ *¬x* = 0

> x AND NOT(x) = 0

* Complementation 2:

> *x* ∨ *¬x* = 1

> x OR NOT( x ) = 1

* Double negation:

> ¬( ¬*x* ) = *x*

> NOT( NOT( x )) = x

* De Morgan law 1:

> ¬*x* ∧ *¬y* = ¬( *x* ∨ *y* )

> NOT( x ) AND NOT( y ) = NOT( x OR y )

* De Morgan law 2:

> ¬*x* ∨ *¬y* = ¬( *x* ∧ *y* )

> NOT( x ) OR NOT( y ) = NOT( x AND y )
## Week 1

### Lecture 2: Graph Basics

- degree - centrality
- clustering coefficient - cohesive
- component(objects: N, interactions: E, system: G(N,E)) - connected

----------------------------------------------------------------------------------------------------------------

- networks(real systems) & graphs(mathematical representation)
- nodes & edges
- directed(arcs) & undirected(symmetric, reciprocal) graphs
- unweighted & weighted graphs
- complete graph
- **adjacency matrix**
- networks are sparse graphs
- degree: node/average/in/out degree
- key graph properties:
  1. **degree distribution**: P(k): normalized histogram P(k)=N_k/N
  2. path length: h distance: shortest path length
  3. **clustering coefficient**: C
  4. connected components: s
- random graph model
  1. degree distribution: Poisson distribution
  2. average path length: O(log n)

### Lecture 3: Ties and Communications

- triadic closure = high clustering coefficient
- bridge & local bridge & span
- strong and weak ties
- **strong triadic closure property**: A node A violates the Strong Triadic Closure property if it has strong ties to two other nodes B and C, and there is no edge at all(either a strong and weak tie) between B and C.
- **Granovetter’s Theorem**: if a node A in a network satisfies the STC property and is involved in at least two strong ties, then any local bridge it is involved in must be a weak tie
- **edge overlap**
- homophily

## Week 2

### Lecture 4: Collective Homophily

- **homophily test**
- correlation in networks: homophily, influence, confounding
- collective classification: local classifier & relational classifier & collective inference
- **probabilistic relational classifier**
- **structural balance property**
- **balance theorem**, bipartite
### Lecture 5: Game Basics

- basic ingredients: player, strategy, utility, payoff
- underlying assumptions: utility, rationality, complete information, independent
- **reasoning about behavior: best response, strictly dominant strategy, equilibrium point**
- prisoners' dilemma
- optimization & game theory
- **Nash equilibrium** (no strictly dominant strategy)

** 在有dominant strategy的情况下，不会converge to mutual benefit; 在有Nash equilibrium的情况下，converge to mutual benefit. --也不一定，可能是对各方都最差的，但一定是最稳定的（两方轮流先选，对方都会选到NE的情况）

- coordination game: focal point, social convention

## Week 3

### Lecture 6: Game Traffic

- anti-coordination game
- **find Nash multiple equilibria & dominant strategy**
- mixed strategy: probability, distribution
- deterministic belief & probabilistic belief
- pure strategy (probability equals 1)
- **expected payoff calculation**
- **mutual best response point & Nash equilibrium**
- **indifference point calculation**
- existence of Nash equilibrium
- **Pareto optimality & social optimality**: It is an ideal system if social optimal is also Nash equilibrium
- **application of Pareto optimality**--线性规划 design space & criterial space & pareto front

## Week 4

### Lecture 7: Mechanism Design Basics

- **Braess's paradox**
- price of anarchy
- auction: participant, strategy, payoff, equilibrium
- auction types:

1. ascending order
2. descending order
3. first-price sealed-bid auctions
4. second-price sealed-bid auctions(social optimal & truth)
---
uid: S000014
name: Either-Or Topology
---
Let $X = [-1,1]$ as a set and declare $U \subset X$ open if and only if $0 \not\in U$ or $(-1,1) \subset U$.

See also:

* Steen, L. A.; Seebach, J. A. (1970), [Counterexamples in Topology](http://books.google.com/books/about/Counterexamples_in_Topology.html?id=DkEuGkOtSrUC), Dover, pp 48-49.
* [Either-or topology](http://en.wikipedia.org/wiki/Either-or_topology) on Wikipedia.

[[Proof of Topology]]
Let $\tau$ be the collection of all open sets $U \subset X$.

Since $(-1,1) \subset X$, we know that $X \in \tau$. Also, since ${0} \notin \emptyset$, we know that $\emptyset \in \tau$.

Let $\mathcal{A}$ be a collection of elements from $\tau$. Two cases arise when considering the union of the elements of $\mathcal{A}$.

The first case is that $(-1,1)$ is a subset of some element in $\mathcal{A}$. Therefore,
$(-1,1) \subset \bigcup\limits_{A \in \mathcal{A}} A \in \tau.$

The second case is that none of the elements of $\mathcal{A}$ have $(-1,1)$ as a subset. Therefore,
$\{0\} \notin \bigcup\limits_{A \in \mathcal{A}} A \in \tau.$

Now let $\{A_1, A_2, \dots, A_n\}$ be a finite collection of elements from $\tau$. Two cases arise when considering the intersection of the elements of $\mathcal{A}$.

The first case is if there is some element of the collection that does not contain $\{0\}$. Thus,
$\{0\} \notin \bigcap\limits_{i = 1}^n A_i \in \tau.$

The second case is if $\{0\}$ is in every element of the collection. If this occurs, then $(-1,1)$ must be a subset of every element in the collection to ensure all elements of the collection remain open. Thus,
$(-1,1) \subset \bigcap\limits_{i = 1}^n A_i \in \tau.$


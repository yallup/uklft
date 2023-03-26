---
marp: true
theme: socrates
paginate: true
author: David Yallup
style: |
  .columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
  }

---


<!-- <style>
section {
  font-size: 28px;
}
  img[alt~="center"] {
  display: block;
  margin: 0 auto;
  }

  justify-content: flex-start;
</style> -->

<style>
   .font-size: 20px;
    
    img[alt~="center"] {
    display: block;
    margin: 0 auto;
    }

  justify-content: flex-start;


   .cite-author {
      text-align        : right;
   }
   .cite-author:after {
      color             : orangered;
      font-size         : 125%;
      /* font-style        : italic; */
      font-weight       : bold;
      font-family       : Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
      padding-right     : 130px;
   }
   .cite-author[data-text]:after {
      content           : " - "attr(data-text) " - ";      
   }

   .cite-author p {
      padding-bottom : 40px
   }

</style>




<!-- _class: titlepage -->

# Nested Sampling for Lattice Field Theory
### David Yallup (<dy297@cam.ac.uk>)
#### 27th March 2023
##### UKLFT meeting

![height:100px](./assets/cam.png)
Live slides with animation available:
[[yallup.github.io/uklft]](https://yallup.github.io/uklft) 


----
<!-- paginate: true -->



## Nested Sampling

Technique for computation of multidimensional integrals [[Ashton et al - Nature review paper]](https://arxiv.org/abs/2205.15570)
> Widespread adoption in Bayesian evidence integrals 

$$ P(\theta | X) = \frac{\mathcal{L}(X | \theta)\times \Pi(\theta) }{Z}\, $$
$$ Z(\beta) = \int D\theta \mathcal{L}(X | \theta)\Pi(\theta) $$

Cambridge Cosmology (KICC and Cavendish AP) one of the driving forces in development: 
* DY (Inference and ML applications) 
* Will Barker (Gravity on the lattice)
* Will Handley (all of the above)
* Boris Deletic (Part III student, gradients in NS)

----
### What does this bring to the table

Rather than a ensemble of chains, construct a chain of ensembles
[[Original paper - Skilling]](https://projecteuclid.org/journals/bayesian-analysis/volume-1/issue-4/Nested-sampling-for-general-Bayesian-computation/10.1214/06-BA127.full)
[[Our implementation, PolyChord - Handley et al]](https://arxiv.org/abs/1506.00171)

<!-- ![bg right](./assets/himmelblau.png) -->

![w:710](./assets/himmelblau.gif) ![w:400](./assets/himmelblau.png)

$$
f(x) \propto -\exp [(x^2 + y -11)^2 + \\ (x + y^2 -7)^2]
$$

----


![bg 80%](./assets/beta_flow.gif)


----


<!-- _class: invert lead -->

# __Conclusion__


<center>

## Thanks for listening


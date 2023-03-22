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

# Evidence is all you need
## Nested Sampling for Lattice Field Theory
### David Yallup (<dy297@cam.ac.uk>)
#### 24th Feb 2023
##### UKLFT meeting

![height:100px](./assets/cam.png)
Live slides with animation available:
[[yallup.github.io/uklft]](https://yallup.github.io/uklft) 


----
<!-- paginate: true -->

<!-- _class: invert lead -->

# __info__


----

### Himmelblau function


$$

f(x) \propto -\exp [(x^2 + y -11)^2 + \\ (x + y^2 -7)^2]

$$

Multimodal function, (exponential of square ~ Gaussian)

Four identical local maxima


![bg right](./assets/himmelblau.png)

----

![bg](./assets/himmelblau.gif)

----


![bg 90%](./assets/beta_flow.gif)


----


<!-- _class: invert lead -->

# __Conclusion__


<center>

## Thanks for listening


---
layout: default
page: "research"
title: "Research"
---

<div class="w3-container w3-content w3-center">
  <h2 class="w3-text-grey w3-padding-16 w3-center"><i class="fa fa-flask fa-fw w3-margin-right w3-xxlarge w3-text-teal"></i>Research</h2>
  <div class="w3-container w3-white w3-margin-bottom">
    <div class="w3-container">
    </div>
  </div>

  <div class="w3-container w3-card w3-white w3-margin-bottom w3-left-align">
    <div class="w3-container">
      <h2 class="w3-text-grey">Geometric deep learning</h2>
      <img src="/assets/images/research/scnn_screenshot.png" alt="Result of an equivariant NN compared to a CNN." style="float:left;width:30%; min-width: 300px;padding: 20px;">
      <p>
      In Geometric Deep Learning one deals with data that has a non-Eucleadian structure, either by characterizing the structure of the data or by analyzing functions defined on a non-Euclidean domain. It is reasonable to require that a predictive model outputs the same results for two data points that are the same, independently of how the data is stored on a computer. Two different ways of storing a graph should not produce two different results, as two different charts on a manifold should not influence the content of the data on the manifold. Geometric deep learning deals with these issues. <span class="w3-text-teal">[1]</span>
      </p>
      <p>
      In my research I focus on learning vector fields and tensor fields on manifolds, with special attention to the group of 3D rotations \(SO(3)\), based on results by <span class="w3-text-teal">[2,3,4]</span>.
      </p>

      <p>
      Our main contribution is reported in  <span class="w3-text-teal">[5]</span>.
      </p>
      <hr>

      <p><span class="w3-text-teal">[1]</span>
      M. M. Bronstein, J. Bruna, Y. LeCun, A. Szlam, and P. Vandergheynst. Geometric deep learning: going beyond euclidean data. IEEE Signal Processing Magazine, 34(4):18–42, 2017.
      </p>
      <p><span class="w3-text-teal">[2]</span>
      Cohen, T. S., Geiger, M., Koehler, J., & Welling, M. (2018). Spherical CNNs. arXiv, 1801.10130.
      </p>
      <p><span class="w3-text-teal">[3]</span>
      Esteves, C., Allen-Blanchette, C., Makadia, A., & Daniilidis, K. (2020). Learning SO(3) Equivariant Representations with Spherical CNNs. Int. J. Comput. Vision, 128(3), 588–600. doi: 10.1007/s11263-019-01220-1
      </p>
      <p><span class="w3-text-teal">[4]</span>
      Esteves, C., Slotine J., Makadia A (2023). Scaling Spherical CNNs. ICLR 2023.
      </p>
      <p><span class="w3-text-teal">[5]</span>
      Ballerin F., Blaser N., Grong E. (2025). SO(3)-Equivariant Neural Networks for Learning Vector Fields on Spheres. arXiv:2503.09456
      </p>
    </div>
  </div>

  <div class="w3-container w3-card w3-white w3-margin-bottom w3-left-align">
    <div class="w3-container">
      <h2 class="w3-text-grey">Statistics on manifolds</h2>
      <p>In a general Riemannian manifold computing distances between two points is not an easy task. One could do that by following the geodesics and optimizing the initial velocity by gradient descent,
          but this is often a computationally intensive operation. What we are interested in studying is the possibility of defining a commuter metric on such manifolds by preprocessing the manifold and 
          computing distances between a set of points of interest. <span class="w3-text-teal">[1]</span>
      </p>
      <hr>
      <p><span class="w3-text-teal">[1]</span> Grong, E., & Sommer, S. (2021). Most probable paths for anisotropic Brownian motions on manifolds. arXiv, 2110.15634</p>
    </div>
  </div>

  <div class="w3-container w3-card w3-white w3-margin-bottom w3-left-align">
    <div class="w3-container">
      <h2 class="w3-text-grey">Neurogeometry of the visual cortex</h2>
      <img src="/assets/images/research/trym_screenshot.png" alt="Image restoration example" style="float:left;width:30%; min-width: 300px;padding: 20px;">
      <p> This project is based on previous work by Citti and Sarti <span class="w3-text-teal">[1]</span> and subsequent works by
    Boscain et al. <span class="w3-text-teal">[2,3,4]</span> to develop new procedures and algorithms for PDE-based image restoration.</p>
    <p>Equipping the rototranslation group \(SE(2)\) with a sub-Riemannian structure inspired by the visual cortex V1, 
      we propose algorithms for image inpainting and enhancement based on hypoelliptic diffusion. 
      We innovate on previous implementations of the methods by Citti, Sarti and Boscain et al., 
      by proposing an alternative that prevents fading and capable of producing sharper results in a procedure that we call WaxOn-WaxOff. 
      We also exploit the sub-Riemannian structure to define a completely new unsharp using \(SE(2)\), analogous of the classical unsharp filter for 2D image processing, 
      with applications to image enhancement. We demonstrate our method on blood vessels enhancement in retinal scans. <span class="w3-text-teal">[5]</span></p>
  <hr>
      <p><span class="w3-text-teal">[1]</span> G Citti and A Sarti. “A cortical based model of perceptual completion in the
      Roto-translation space”. en. In: J. Math. Imaging Vis. 24.3 (May 2006), pp. 307–
      326.</p>
      <p><span class="w3-text-teal">[2]</span> Ugo Boscain et al. “Anthropomorphic Image Reconstruction via Hypoelliptic
        Diffusion”. In: SIAM j. control optim. 50.3 (Jan. 2012), pp. 1309–1336.</p>
      <p><span class="w3-text-teal">[3]</span> U Boscain et al. “Hypoelliptic diffusion and human vision: A semidiscrete new
        twist”. en. In: SIAM J. Imaging Sci. 7.2 (Jan. 2014), pp. 669–695.</p>
      <p><span class="w3-text-teal">[4]</span> Ugo V Boscain et al. “Highly corrupted image inpainting through hypoelliptic
        diffusion”. en. In: J. Math. Imaging Vis. 60.8 (Oct. 2018), pp. 1231–1245.</p>
      <p><span class="w3-text-teal">[5]</span> Ballerin, F., & Grong, E. (2023). Geometry of the Visual Cortex with Applications to Image Inpainting and Enhancement. arXiv, 2308.07652.</p>
    </div>
  </div>

    
    <div style="padding-top:16px;"></div>
</div>
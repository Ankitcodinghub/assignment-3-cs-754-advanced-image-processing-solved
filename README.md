# assignment-3-cs-754-advanced-image-processing-solved
**TO GET THIS SOLUTION VISIT:** [Assignment 3: CS 754, Advanced Image Processing Solved](https://www.ankitcodinghub.com/product/assignment-3-cs-754-advanced-image-processing-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110527&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Assignment 3: CS 754, Advanced Image Processing Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
1. Download the book ‘Statistical Learning with Sparsity: The Lasso and Generalizations’ from https://web. stanford.edu/~hastie/StatLearnSparsity_files/SLS_corrected_1.4.16.pdf, which is the website of one of the authors. (The book can be officially downloaded from this online source). Your task is to trace through the steps of the proof of Theorem 11.1(b). This theorem essentially derives error bounds on the minimum of the following objective function: Xβk2 +λNkβk1 where λN is a regularization parameter, β∈Rp is the unknown sparse signal, y = Xβ +w is a measurement vector with N values, w is a zero-mean i.i.d. Gaussian noise vector whose each element has standard deviation σ and X ∈RN×p is a sensing matrix whose every column is unit normalized. This particular estimator (i.e. minimizer of J(x) for x) is called the LASSO in the statistics literature. The theorem derives a statistical bound on λ also. Your task is split up in the following manner:

(a) Define the restricted eigenvalue condition (the answer’s there in the book and you are allowed to read it, but you also need to understand it).

(b) Starting from equation 11.20 on page 309 – explain why G(vˆ) ≤ G(0).

(c) Do the algebra to obtain equation 11.21.

(d) Do the algebra in more detail to obtain equation 11.22 (state the exact method of application of Holder’s inequality – check the wiki article on it, if you want to find out what this inequality states).

(e) Derive equation 11.23.

(f) Assuming Lemma 11.1 is true and now that you have derived equation 11.23, complete the proof for the final error bound for equation 11.14b.

(g) In which part of the proof does the bound show up? Explain.

1

(j) Now read Theorem 1.10 till corollary 1.2 and comments on it concerning an estimator called the ‘Dantzig selector’, in the tutorial ‘Introduction to Compressed Sensing’ by Davenport, Duarte, Eldar and Kuttyniok. You can find it here: http://www.ecs.umass.edu/~mduarte/images/IntroCS.pdf. What is the common thread between the bounds on the ‘Dantzig selector’ and the LASSO?

(k) Read the abstract and introduction (section 1) of the paper ‘Square-root lasso: pivotal recovery of sparse signals via conic programming’ by Belloni et al, published in the journal Biometrika. See https: //www.jstor.org/stable/23076172. This paper proposes an estimator called the square-root LASSO. What is the advantage of the square-root LASSO over the LASSO? [2 x 8 + 6 + 4 + 4 = 30 points]

2. In this task, you will you use the well-known package L1 LS from https://stanford.edu/~boyd/l1_ls/. This package is often used for compressed sensing solution, but here you will use it for the purpose of tomographic reconstruction. The homework folder contains images of two slices taken from an MR volume of the brain. Create measurements by parallel beam tomographic projections at any 18 randomly angles chosen from a uniform distribution on [0,π). Use the MATLAB function ‘radon’ for this purpose. Now perform tomographic reconstruction using the following method: (a) filtered back-projection using the RamLak filter, as implemented in the ‘iradon’ function in MATLAB, (b) independent CS-based reconstruction for each slice by solving an optimization problem of the form J(x) = ky−Axk2 + λkxk1, (c) a coupled CS-based reconstruction that takes into account the similarity of the two slices using the model given in the lectures notes on tomography. For parts (b) and (c), use the aforementioned package from Stanford. For part (c), make sure you use a different random set of 18 angles for each of the two slices. The tricky part is careful creation of the forward model matrix A or a function handle representing that matrix, as well as the corresponding adjoint operator AT. Use the 2D-DCT basis for the image representation. Modify the objective function from the lecture notes for the case of three similar slices. Carefully define all terms in the equation and re-implement it. [3+7+8+7 = 25 points]

3. Prove the following properties of the Radon transform:

(a) Shifting: R(g(x − x0,y − y0))(ρ,θ) = R(g(x,y))(ρ − x0 cosθ − y0 sinθ,θ). Here ρ is the offset and θ is the angle of projection.

(b) Rotation: Let g0(r,ψ) = g(r,ψ−ψ0). Then prove that R(g0)(ρ,θ) = R(g)(ρ,θ−ψ0). R(g0)(ρ,θ) = R(g)(ρ,ψ0− θ

(c) Convolution: Given image f(x,y) and kernel k(x,y), show that Rθ(f∗k) = Rθ(f)∗Rθ(k), where ∗ is the convolution operation. In other words, the Radon transform of the convolution of two signals is equal to the convolution of the Radon transform of the individual signals (in the same angles). [8+5+7=20 points]

4. For a sensing matrix with columns having unit magnitude, with s-order restricted isometry constant δs and mutual coherence µ, prove that δs ≤ (s − 1)µ. (Hint: Use Gershgorin’s disc theorem.) [10 points]

5. Here is our Google search question again. You know of the applications of tomography in medicine (CT scanning) and virology/structural biology. Your job is to search for a journal paper from any other field which requires the use of tomographic reconstruction (examples: seismology, agriculture, gemology). State the title, venue and year of publication of the paper. State the mathematical problem defined in the paper. Take care to explain the meaning of all key terms clearly. State the method of optimization that the paper uses to solve the problem. [15 points]

2

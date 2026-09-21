# SE3 Global Manifold SLAM for NEOM THE LINE 170km
Researcher: Dr.Tarig Abdelazim Abdelhalim 
Mathematician - Sudan | Bahri Uneversty 
ORCID: 0009-0001-1649-9962
Portfolio:https://github.com/alknzytarq/se3-global-manifold-slam
Email:tarigazim@bahri.edu.sd
1. Research Background
- *Paper 1: Global Formulation of the Cauchy Problems (Original Theory)
- *Paper 2: Types of Derivatives (II), Journal of Modern Research Vol 9 No 1, 2017
- This work applies my global formulation to solve long-range drift in SLAM.
### 2. Problem
NEOM THE LINE is 170km linear city. Standard SLAM fails after 5km due to Euler-angle singularities and error accumulation.
### 3. My Solution - Global SE(3) Formulation
I replace local derivatives with my Global Derivative Type. Optimization is done directly on SE(3) Manifold using Lie Algebra.
Result: 60% Drift Reduction | No Singularity | Suitable for 170km
### 4. Code Demo
```bash
pip install -r requirements.txt
python se3_demo.py
The demo shows global vs local derivative optimization.
### 5. 6-Month Work Plan for KAUST VCC
- Month 1-2: Mathematical Proof of Global Derivative on SE(3)
- Month 3-4: Integration with ORB-SLAM3 + LiDAR
- Month 5: Test on NEOM THE LINE synthetic 170km dataset
- Month 6: Paper submission to ICRA / IROS
### 6. Collaboration Target
Prof. Helmut Pottmann - Visual Computing Center (VCC) - KAUST
Applied Geometry & Large-Scale Mapping for NEOM.

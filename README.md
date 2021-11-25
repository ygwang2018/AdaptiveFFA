# AdaptiveFireflyAlgorithm
The source code for the case study of Chapter 7 of Ryan's PhD thesis. In this chapter, an adaptive firefly algorithm is proposed for global continuous optimization problems.

An improved firefly algorithm for global continuous optimization problems

Global continuous optimization is populated by its implementation in many real-world applications. Such optimization problems are often solved by nature-inspired and meta-heuristic algorithms, including the firefly algorithm (FA), which offers fast exploration and exploitation. To further strengthen FA’s search for global optimum, a Levy-flight FA (LF-FA) has been developed through sampling from a Levy distribution instead of the traditional uniform one. However, due to its poor exploitation in local areas, the LF-FA does not guarantee fast convergence. To address this problem, this paper provides an adaptive logarithmic spiral-Levy FA (AD-IFA) that strengthens the LF-FA’s local exploitation and accelerates its convergence. Our AD-IFA is integrated with logarithmic-spiral guidance to its fireflies’ paths, and adaptive switching between exploration and exploitation modes during the search process. Experimental results show that the AD-IFA presented in this paper consistently outperforms the standard FA and LF-FA for 29 test functions and 6 real cases of global optimization problems in terms of both computation speed and derived optimum.

See: https://www.sciencedirect.com/science/article/pii/S0957417420301652


Please cite as:

@article{wu2020improved,
  title={An improved firefly algorithm for global continuous optimization problems},
  author={Wu, Jinran and Wang, You-Gan and Burrage, Kevin and Tian, Yu-Chu and Lawson, Brodie and Ding, Zhe},
  journal={Expert Systems with Applications},
  volume={149},
  pages={113340},
  year={2020},
  publisher={Elsevier}
}

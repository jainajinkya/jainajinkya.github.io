---
layout: page
title: Research
permalink: /research/
---
<div class="toc">
  <ul class="texts"> 
      <li class="text-title">
      <b> Efficient Hierarchical Robot Motion Planning Under Uncertainty and Hybrid Dynamics </b>
      	<p> Noisy observations coupled with nonlinear dynamics pose one of the biggest challenges in robot motion planning. By decomposing the nonlinear dynamics into a discrete set of local dynamics models, hybrid dynamics provide a natural way to model nonlinear dynamics, especially in systems with sudden "jumps" in the dynamics, due to factors such as contacts. We propose a hierarchical POMDP planner that develops locally optimal motion plans for hybrid dynamics models. The hierarchical planner first develops a high-level motion plan to sequence the local dynamics models to be visited. The high-level plan is then converted into a detailed cost-optimized continuous state plan. This hierarchical planning approach results in a decomposition of the POMDP planning problem into smaller sub-parts that can be solved with significantly lower computational costs. The ability to sequence the visitation of local dynamics models also provides a powerful way to leverage the hybrid dynamics to reduce state uncertainty. We evaluate the proposed planner for two navigation and localization tasks in simulated domains, as well as an assembly task with a real robotic manipulator. <a href="http://proceedings.mlr.press/v87/jain18a/jain18a.pdf" target="_blank"> [paper]</a> <a href="https://github.com/Pearl-UTexas/POMDP-HD" target="_blank"> [code]</a> </p>    	
     	<iframe width="560" height="315" src="https://www.youtube.com/embed/Y9BoNvI0K5c" frameborder="0" allowfullscreen></iframe> <br> <br><br><br>
    </li>
    <li class="text-title">
      <b> Reachable Belief Space Estimation in POMDPs via Lyapunov Functions </b>
        <p> Partially observable Markov decision processes (POMDPs) are a formalism used to study  autonomous agents making decisions in uncertain environments. Since the states of a POMDP are not directly observable, through interactions with the environment and receiving observations, the agent updates its probabilistic {belief} in the true state. Despite the fact that  POMDPs provide a unique modeling paradigm,  they are undecidable to solve exactly in general. Therefore, many approximate point-based methods exist for studying POMDPs. But, these methods rely on discretization of the belief space and are prone to errors, which has made the application of POMDPs in safety-critical scenarios limited. In this paper, we use notions from control theory to assure that the solutions of a POMDP remain in a subset of the belief space without the need to solve or approximate the POMDP. To this end, we first demonstrate that the evolutions of the beliefs for a given POMDP can be represented as a discrete-time switched system. We then use Lyapunov functions to find approximations of the reachable belief space for a given initial belief. Once such a set is computed, we show how we can verify whether a set of reach-safe objectives is satisfied. From a computational standpoint, we demonstrate that the search for the Lyapunov functions can be carried out by polynomial optimization. We apply our theoretical results to estimate the reachable belief space for a robot manipulation task of assembling a toy airplane.</p>
    </li>


<!--     <li class="text-title">
      <b> Robot manipulation planning under uncertainty using hybrid dynamics </b>
      	<p> The difficulty of many robot manipulation tasks stems from stochasticity and partial observability coupled with highly nonlinear dynamics. However, much of the nonlinearity in manipulation tasks can be explained by sudden changes in contact or articulated state. This fact allows the dynamics to be naturally factored into a discrete set of simpler models combined together as a hybrid dynamics model. To leverage these hybrid dynamics for efficient planning under uncertainty, we introduce a novel POMDP planner that computes and stabilizes around trajectories in a hybrid belief space. We evaluate the proposed planner in both a simulated navigation domain, as well as an assembly task with a real robotic manipulator. Experiments on robot doing a partial assembly of Toy airplane from the YCB Dataset <a href="/files/hblqr.pdf" target="_blank"> [manuscript]</a> </p> 
      	
     	<iframe width="560" height="315" src="https://www.youtube.com/embed/IMLakQdTi6c" frameborder="0" allowfullscreen></iframe>
    </li> -->
  </ul>
</div>
---
layout: post
title:  "Dynamic Hedging of Barrier Option"
date:   2022-11-15 13:52:27 +0800
categories: jekyll update
---

# Introduction  

Barrier option is a derivative whose payoff is dependent on whether the underlying asset's price breaches a barrier during it lifetime. When it goes to maturity, the payoff of the barrier option is either vanilla option or zero depending on whether its underlying asset's price breaches a barrier during it lifetime. The 'Down and out' barrier option means it has a barrier $$B < S_0$$  and if the underlying asset's price doesn't down-cross the barrier $$B$$ during its lifetime, the final payoff is a vanilla option. If the underlying asset's price down-cross the barrier $$B$$, its final payoff is zero. For 'Down/Up and out' options is called 'Knock-out' option since the behavior of the underlying asset's price crossing the barrier is called 'knock-out'. Similarly, The 'Down and in' barrier option means it has a vanilla option payoff if the underlying asset's price does down-cross the barrier $$B$$ during its lifetime and has no payoff if the underlying asset's price doesn't down-cross the barrier $$B$$. 'Down/Up and in' options are called 'Knock-in' option since the behavior of the underlying asset's price crossing the barrier is called 'knock-in'. We denote the Down and In Put option with barrier $$B$$ and strike $$K$$ as 'DIP' or 'B DI K put'. 

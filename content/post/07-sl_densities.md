+++
title = "Super Learning of densities with the `sl3` and `condensier` R packages"
description = "An examination of density estimation within the Super Learning framework"
author = "Nima Hejazi"
date = "2018-02-28"
menu = "main"
draft = false
+++

Woah, __seventh__ lab meeting already! Today, we'll continue our ongoing
discussion of Super Learner, this time taking a look at how to perform density
estimation within this framework. We'll begin by thinking about the motivations
behind density estimation, and then move on to why we might want to perform
density estimation using cross-validation. To make these ideas concrete, we'll
walk through how to use the [`condensier` R
package]() to perform density
estimation. Finally, we'll combine
[`sl3`](https://github.com/jeremyrcoyle/sl3) and
[`condensier`](https://github.com/osofr/condensier) together to fit
data-adaptive ensemble models of densities.


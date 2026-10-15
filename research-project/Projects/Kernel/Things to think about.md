# May Presentation 
+ Split population is cross validation
+ Constant moral hazard as right censored (having little to no parametric assumption is bad? By saying any part of the data you need to make some assumptions on the part of the support you don’t) need a good reason why (need some theory on how *observed ppl are similar to non observed*) 
	+ "The structural assumption here is **Proportional Odds / Parallel Hazards across cohorts**—that the relative risk of dropout across grades shifts in parallel across birth cohorts" 
	+ i.e. that there should be similar trends, since earlier cohorts have been better 
	+ basically need some structural matching theory 
	+ but this is the assumption form older -- borrows support form older cohorts 
+ - The big issue that I flagged bears repeating. It's not at all clear to me how you simultaneously deal with censoring while being "less" parametric. I'd like to see more intuition here.
	+ From AI: The assumption being made is **local smoothness in feature space** $X$ (that subjects with similar attributes have similar hazard profiles), rather than imposing a linear or log-proportional functional form on

Bounding issue! 

# Thoughts
+ component - wide censoring ?
+ informative vs nn infomrative occurences 
+ null would be non-informative censorign i.e. risk set is a randome sub poop of risk pop when non fnomrative
	+ and this makes sense because if there is no ptternt to the censoring then there is no reason for the risk set to be different
		+ first need to find data for risk set 
	+ could test on information?
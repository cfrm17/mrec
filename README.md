# Market Risk Economic Capital Introduction

Financial business is exposed to many types of risks due to the nature of business. To guard against the risk, financial institutions must hold capital in proportion to the potential risk. Market risk economic capital is intended to capture the value change due to changes in market risk factors. It is an internal capital reserve to cover unexpected loss due to market movement. 

Economic capital falls into the category of Value at Risk (VaR) measures as both try to capture value change due to market movement. Most institutions use the existing VaR system to compute economic capital. VaR captures the market risk of 1-day time period at 99% confidence level whereas Economic capital measures the market risk of 1-year time period at 99.95 confidence level. Therefore, scaling methodology is the key to compute economic capital, i.e., scaling 1-day to 1-year and 99% to 99.95%. This presentation is intended to answer several fundamental economic capital questions: what is economic capital? What is the difference between economic capital and regulatory capital? How to compute economic capital? 

Keywords
Economic capital, market risk, VaR, unexpected loss, time horizon scaling, confidence level scaling, regulatory capital.


	Background
	Financial business is exposed to many types of risks due to the nature of business.
	To guard against the risk, financial institutions must hold capital in proportion to the potential risk.
	Market risk economic capital is intended to capture the value change due to changes in market risk factors.

	Economic Capital (EC) Definition
	Economic loss is the loss in economic or market value due to market movement.
	EC is intended to cover unexpected losses rather than expected loss, illustrated as follows.

	Economic Capital vs Regulatory Capital
	Economic Capital
	EC is an internal measure for internal risk control purpose.
	EC is statistically measured for 1-year time period at 99.95% confidence level (consistent with the probability of default (0.05%) targeted by most institutions)
	Regulatory Capital
	Regulatory capital is an external measure used by regulators.
	RC is statistically measured for 10-day time period at 99% confidence level

	Economic Capital Calculation
	Economic capital falls into the category of Value at Risk (VaR) measures as both try to capture value change due to market movement.
	Most institutions use the existing VaR system to compute economic capital.
	VaR captures the market risk of 1-day time period at 99% confidence level
	Economic capital measures the market risk of 1-year time period at 99.95 confidence level
	Scaling methodology is the key to compute economic capital, i.e., scaling 1-day to 1-year and 99% to 99.95%

	Economic Capital Scaling Methodology
	Time horizon Scaling
	The simplest and most common used approach: scaling 1-day VaR to 1-year VaR as
1-year VaR at 99% confidence level = √T * 1-day VaR at 99% confidence level
where T = 365 for accounting for calendar days only or T = 250 for accounting for business days only
	Assumption of using this scaling formula
	1-day portfolio loss distribution is independent and identically distributed (IID)
	Constant mean and volatility
	No autocorrelation
	Pros and Cons
	Pros
Very simple and intuitive
	Cons
This scaling approach is most likely under-estimated risk given the assumptions don’t match the reality.
	Confidence level scaling
	How to scale 1-year VaR at 99% confidence level to 1-year VaR at 99.95% confidence level
	There are many different approaches.
	One approach popularly used in market and also discussed in literature is based on Extreme Value Theory.
	Assuming the loss distribution follows t-distribution, the scaling factor for confidence level change is given by
K=((1-99%)/(1-99.95%))^r

where r needs to be calibrated based on 1-year loss distributions

	Final economic capital
EC = 1-year 99.95% VaR = K*√T*1-day 99% VaR
Where VaR include general VaR, equity specific VaR, debt specific VaR and incremental risk charge (IRC)



References:

https://finpricing.com/lib/FxVolIntroduction.html

https://bitbucket.org/cfrm17/mrec/downloads/mrEc-11.pdf


# Python-package-for-dynamic-panel-model
This particular repository focuses on typical dynamic panel data model
The data used were collected from the National Longitudinal Survey of Youth (NLSY) tracking the lives of individual youths across their life. They consist of 1,188 individuals born between 1957-1964.
log(yit)=λ1yi,t−1+λ2yi,t−2+β1Sit+β2Xit+β3X2it+β4D+ϵ

Where logy denotes income, S is years of schooling, and X is years of experience since finishing school. Therefore, the exponent on S can be considered the ‘return to education’ and the exponent on X the ‘ return to experience.’ D is a vector of control variables such as IQ, Sex, Race and Marital status. The quadratic form of the experience variable captures non-linearities in the impact of experience on earnings

The following topics are covered:

•	Difference and System GMM

•	One-step, two-step, and iterative estimates

•	First-difference and forward orthogonal deviation transformations

•	Robust standard errors. For two-step GMM, the calculation suggested by Windmeijer (2005) is used.

•	Hansen over-identification test

•	Arellano-Bond test for autocorrelation

•	Time dummies

•	Collapse GMM instruments to limit instrument proliferation.

•	Search for models based on users' request, rather than just run the model specified by users as other packages.

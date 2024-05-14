Please read the Arron-Hyman-Candidate-Lab.pdf for details on how to run the submission.

The code snippets and links to the live code are available in this submission. Along with how to run each task, as well as how to setup the task within LaunchDarkly.

The application has been uploaded online which should ease the process of analyzing my submission.

The two main websites accessed within this file are buyhomedesigns.com and greathousedesign.com at the following URLs.

They both use the same code and plugin for their online marketplace but have been segmented out within LaunchDarkly to behave differently.



Home Search page that contains the discount code
https://www.buyhomedesigns.com/marketplace/

Product Page that contains a discount code and the "Out of country" message for those outside of the United States
https://www.buyhomedesigns.com/marketplace/home-plan/?plan_id=001-3912



To verify that the target segment directed towards buyhomedesign.com is working, we will validate that Great House Design does not see any of the coupon options.

Home Search page that hides the discount code
https://www.greathousedesign.com/plan-search/

Product Page that hides the discount code but keeps the  "Out of country"  message for those outside of the United States
https://www.greathousedesign.com/home-plan/?plan_id=001-3912


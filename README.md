# Gut microbiome and vascular ageing in a multi-ethnic population - The HELIUS study

This project, part of my PhD thesis, focuses on the association between gut microbiota (GM) and vascular ageing (VA), evaluating the role of sex and ethnicity as potential effect modifiers.

# 1. Rationale

The burden of cardiovascular disease (CVD) is projected to increase due to ageing populations and suboptimal prevention. Current diagnostic tools and interventions mainly target the later stages of CVD aetiology; however, underlying processes such as VA might offer a promising window opportunity for early intervention. Although the mechanisms linked to VA have been extensively studied, consensus on a comprehensive definition and measure is still lacking. Age and the cumulative effect of traditional cardiovascular risk factors contribute to  reducing the adaptability of the cardiovascular system and increase the risk of CVD. As a result, arterial stiffness (AS), endothelial dysfunction, reduced peripheral arterial circulation, and blood pressure (BP) alterations establish a vicious cycle heading to vascular dysfunction, a hallmark of VA. Direct measures of AS and central hemodynamics, such as pulse wave velocity (PWV), central blood pressure (CBP), and augmentation index (AIx), are strong predictors of fatal and non-fatal CVD, and all-cause mortality. Therefore, VA could play a pivotal role in enhancing risk prediction tools and age-targeted interventions.

Concurrently, recent evidence suggests that changes in GM composition and derived metabolites might increase the risk of chronic diseases, including CVD. The GM, directly and indirectly, influences VA and CVD by participating in BP, vascular inflammation, stiffness regulation, as well as lipid and glucose metabolism. Moreover, VA and GM composition significantly vary across ethnic groups and sex, offering a promising starting point for understanding and addressing cardiovascular risk disparities early in the CVD pathway. 

Despite the growing evidence, unravelling the effects of the GM on VA, as well as understanding the role of sex and ethnicity in this association, remains an unsolved gap. Furthermore, most studies have not adequately adjusted for important confounders, particularly BMI and dietary factors. For these reasons, we aim to investigate the role of GM on the most researched VA markers from a multi-ethnic perspective. The insights gained from this study may contribute to closing this knowledge gap and provide relevant elements to guide clinical practice and future research.

# 2. Aim

To address the cross-sectional association between gut microbiota composition and vascular ageing traits and whether ethnicity and sex modify this association, using data from the HELIUS study.

# 3. Methods

Cross-sectional study using baseline information from the ongoing HEalthy Life In an Urban Setting (HELIUS) study collected between 2011 and 2015. The methods and cohort profile of the HELIUS study have been published elsewhere. Briefly, the HELIUS study is a prospective cohort study among six large ethnic groups living in Amsterdam, the Netherlands. The baseline included 24,789 participants (aged 18–70 years), representing Dutch, African Surinamese, South-Asian Surinamese, Ghanaian, Turkish and Moroccan origins. For the present study, we will include approximately 3,000 participants with available baseline information on gut microbiota profile, VA markers, as well as demographic and clinical variables of interest. 

Fecal samples were collected and gut microbiome composition was determined using 16S rRNA sequencing. Different markers of VA will be considered. The Arteriograph system (Tensiomed Kft., Budapest, Hungary) was used to assess aortic pulse wave velocity (AoPWV), augmentation index (AIx), and CBP. The pulse pressure amplification (PPA) and reflection magnitude (RM), two novel and promising markers, were determined using the Nexfin™ device (Edwards Lifesciences BMEYE, Amsterdam, The Netherlands). Associations between GM composition and each VA marker will be assessed using linear regression models using the R package MaAsLin2, designed to estimate multivariable-adjusted associations between metadata and microbial features. When possible, VA markers will be dichotomized using the cut-off points reported in the literature. In these cases, we will fit logistic regression models. Final models will be adjusted for potential confounders based on the Directed Acyclic Graphs (DAG). 

# 4. Analysis


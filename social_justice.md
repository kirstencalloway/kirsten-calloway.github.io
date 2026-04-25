# The Non-Neutrality of Data: Measurement Bias, Multiracial Erasure, and the Imperative for Context- and Identity-Conscious Structural Redesign

**Kirsten L. Calloway**
Howard University, Capstone Portfolio

---

## The Problem Statement

Multiracial individuals, particularly Black-White biracial people, are systematically underrepresented in the measurement systems that shape research, policy, and clinical decision-making. This pattern is documented across psychological assessment, clinical algorithms, census classification, and artificial intelligence. The monoracial logic structuring these systems does not reflect the complexity of racial identity; it reflects institutional histories of administrative racial management (Benthall & Haynes, 2019). When systems offer only monoracial options, they do not misclassify multiracial people. They exclude the possibility of multiracial identity from the categories available.

The U.S. Census Bureau reported a 276% increase in the multiracial population between 2010 and 2020 (Jones et al., 2021), though Ventura and Flores (2025) demonstrated that much of this growth reflects changes in data processing — showing that measurement systems actively construct demographic visibility rather than passively recording it. At 10.2% of the U.S. population, multiracial individuals remain collapsed into "Other," grouped with missing data, or excluded from validation samples entirely.

Benthall and Haynes (2019) documented how racial categories migrate from census policy and legal definitions into machine learning through training data, creating a self-perpetuating cycle of classification, sorting, and disparity. Benjamin (2020) describes this process as the "New Jim Code," in which new technologies inherit and extend racial hierarchies under the appearance of neutrality. Sablan (2019) demonstrates that instruments developed within dominant cultural frameworks may not capture the strengths of non-dominant populations, a limitation rooted not in the methodology itself but in the assumptions governing what the instrument was built to measure.

## The Findings

My capstone research empirically tests this principle. Using VIA Institute data (n = 7,047), I examined character strength patterns across three racial groups: Monoracial Black (n = 441), Monoracial White (n = 2,868), and Black-White Biracial (n = 3,738). This analysis is grounded in Dr. Joseph L. White's (1984) documentation of seven psychological strengths in Black communities — improvisation, resilience, connectedness to others, spirituality, emotional vitality, gallows humor, and healthy suspicion of dominant systems — strengths he identified as adaptive responses decades before positive psychology emerged as a field. Dr. Jacqueline Mattis's scholarship on generational hope (Hellman & Mattis, 2023) provides additional theoretical support for examining Hope as a variable.

Hope demonstrates the strongest association with resilience among all 24 character strengths (r = .459, p < .001). Monoracial Black participants report the highest Hope scores (M = 4.10) compared to Black-White Biracial (M = 3.79) and Monoracial White (M = 3.76). A two-way ANOVA confirmed a significant main effect of race (F = 45.43, p < .001) with no significant interaction between race and geography (F = 0.44, p = .642), indicating that Hope endures for Monoracial Black participants regardless of geographic context.

The constellation analysis produced findings with direct implications for this social justice discussion. When character strengths are ranked within each racial group, Spirituality, Gratitude, and Hope appear in the Monoracial Black top 10 but are entirely absent from both the Black-White Biracial and Monoracial White top 10s. Dr. White identified spirituality as one of his seven key psychological strengths in Black communities. The co-occurrence of these three strengths, and their collective absence from both other groups, suggests they may function as interconnected community resources shaped by lived experience rather than as isolated individual traits. These patterns became visible when I disaggregated the data.

The VIA assessment itself represents a limitation that is also a social justice concern. The Hope scale measures individual, goal-oriented hope rather than what Dr. Mattis calls generational hope: hope that transcends individual lifetimes, hope as intergenerational survival. If the most widely used character strengths instrument cannot measure the forms of hope that Dr. White documented in Black communities, then the finding that Monoracial Black participants score highest likely underestimates the true difference.

This measurement limitation parallels a computational one. The International Warfarin Pharmacogenetics Consortium's dosing algorithm categorizes all multiracial patients under a single "Missing or Mixed" designation, grouping them with patients whose racial data is absent entirely (International Warfarin Pharmacogenetics Consortium, 2009). Pharmacogenetic research has shown that standard dosing algorithms explain dramatically less dose variability for admixed populations (approximately 4%) compared to Asian (approximately 70%) or Black (approximately 40%) populations, meaning the predictive model functionally collapses for multiracial patients. Across both psychological and computational domains, foundational design assumptions — rather than technical limitations — produce the erasure.

## Advocacy and Recommendations

These findings indicate a need for structural redesign at multiple levels.

For researchers and scale developers, new instruments should be grounded in the communities they claim to measure. Sablan (2019) demonstrates this is possible: her development of nondominant cultural capital scales, validated through cultural expert review and cognitive interviews, offers a model for building instruments from within communities rather than imposing frameworks from outside them. I recommend developing a Generational Hope Scale with items reflecting intergenerational, collective, resistance-based hope, and a scale measuring Dr. White's seven psychological strengths, which no validated instrument currently captures.

For data scientists, following QuantCrit principles (Gillborn et al., 2018) means refusing to treat racial categories as natural inputs and interrogating the assumptions embedded in models' default settings. Olteanu et al. (2019) identify intervention points at every stage of the data pipeline, from collection through processing to evaluation.

For policymakers, algorithmic accountability legislation should mandate transparency in how racial categories are constructed and used in high-stakes systems. As Noble (2018) argues, meaningful change requires public accountability and structural alternatives to information infrastructure built without the communities it claims to serve.

Without structural redesign, multiracial populations will continue to be measured by instruments not validated for their experiences and excluded from the fairness testing applied to other demographic groups. Centering historically excluded voices in the redesign of measurement systems is a requirement for equity.

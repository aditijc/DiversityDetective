# DiversityDetective
Using ML to extract information from a Glassdoor gender pay gap dataset.

## Our Inspiration
Gender disparity in the workforce is the unequal treatment of men and women when it comes to employment opportunities, wages, and overall career progression. Despite significant progress in recent decades, there is still a significant gender gap in many workplaces, with men typically earning more money, receiving more promotions, and occupying more senior positions than women.

It is essential for both employers and employees to be aware of this gender disparity and to take steps to address it. Both employers and employees can play an active role in addressing gender disparity in the workforce by advocating for themselves and others, speaking up against discrimination and harassment, and supporting policies and initiatives that promote gender equality.

Awareness is the first step in taking action. We propose DiversityDetective, a machine learning tool to address difficulties in detecting and handling gender disparity amongst both employees and employers in the workforce. We believe that DiversityDetective can help promote gender equality and create a more inclusive and diverse workplace.

## What it Does
DiversityDetective is a quantitative tool designed to help employers verify that they are not treating their female and male employees differently. The tool uses a machine learning clustering model to group employees into clusters based on similar merit. By visualizing the mean features for each cluster, as well as the percent gender makeup of the clusters, employers can identify groups of employees that are treated similarly or differently by their employer.

The tool's clustering model allows for a more in-depth analysis of employee information, enabling employers to see beyond the surface level and identify potential instances of bias. For example, the tool may group together a cluster of lower-paid employees who have less experience than other employees, which would not indicate gender bias. However, the tool may also identify a lower-paid cluster with similar experience to other clusters but with a higher percentage of women, indicating potential gender bias.

By identifying these clusters, employers can spot potential unconscious bias and take steps to address it. For instance, they can review their hiring and promotion practices, evaluate their compensation structures, and provide training to their managers on how to avoid unconscious bias. 

DiversityDetective also incorporates SHAP feature attribution results to show how important different features are in a model’s predictions. Interestingly, SHAP ranked gender within the top 5 important features, which highlights the significance of gender in the tool's analysis and emphasizes the need for employers to actively monitor and address potential gender bias in their workplace.

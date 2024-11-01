#Motivation and Background#
SDGs and UNICEF
The United Nations (UN) Sustainable Development Goals (SDGs) are targets for global development that were adopted in 2015. All countries have agreed to work towards achieving them by 2030.

The United Nations International Children’s Emergency Fund (UNICEF) is the custodian or co-custodian of 19 global SDG indicators Links to an external site.. In this role, UNICEF supports countries in generating, analyzing, and using data for these indicators for all their citizens. This includes leading methodological work, developing international standards, and establishing mechanisms for the completion and verification of national data. UNICEF also helps to maintain global databases.

UNICEF works in over 190 countries and territories to save children’s lives, defend their rights, and help them fulfil their potential Links to an external site. from early childhood through adolescence. Country offices develop an “outcome-output” structure as part of country programme planning.

Country Programmes
Country programmes articulate UNICEF’s strategic contribution to national efforts towards the realization of child rights and the achievement of the 2030 Agenda for Sustainable Development. They align with national development priorities, respond to the national context, and build on a risk-informed analysis of the situation of all children, adolescents and women, as well as on achievements, lessons learned from previous cooperation, and opportunities for equitable development.

The Country Programme Document (CPD) is prepared in partnership with the Government and relevant in-country stakeholders and with the technical collaboration of regional offices and Headquarters divisions. Additionally, the CPD provides a basis for the measurement of country programme performance.

 

#Motivating Challenge#
As we pass the halfway point to 2030, UNICEF is searching for opportunities to accelerate their contributions to SDG progress. UNICEF’s decentralized and hierarchical structure means that there aren’t mature mechanisms and strong practices for sharing knowledge and analysis across various country offices, especially for countries that sit under different UNICEF Regional Offices. New or innovative approaches to designing or implementing programme interventions that have a high impact may not be well-known in other locations where the lives of children would also be positively impacted.

 

#Data Context#
To explore this question, let’s use the analogy of a vehicle to represent a country on its journey to reaching the SDG goals.

 

Country Context ("Terrain")
We regard the country’s current situation and context (social, demographic, and/or economic indicators) as the “terrain” that the vehicle is traversing. More challenging terrain may reduce the speed of travel compared to other countries where the terrain is smoother. This means that programme interventions that are highly effective in one type of terrain may not be effective in more challenging terrain (i.e. the vehicles need to be outfitted with different equipment).

UNICEF has identified 1300+ country context indicators that we can use to characterize each country’s ‘terrain’, which include:

Statistical tables from UNICEF’s 2023 State of the World's Children report Links to an external site.
Indicators from UNDP’s Human Development Report Links to an external site.
World Bank’s World Development Indicators Links to an external site.
Fund for Peace’s Fragile States Index Links to an external site.
 

SDG Progress ("Distance")
We can think of the progress towards SDGs as the current “distance” the vehicle has travelled so far from its starting point on the way to its final destination. There may be greater opportunities to accelerate our contributions to SDG progress in countries further from the final destination, or potentially different approaches to reverse the direction of countries that are headed in the wrong direction.

We will track this distance using the Sustainable Development Report Links to an external site.’s SDG Index Score. The overall score measures the total progress towards achieving all 17 SDGs. It can be interpreted as a percentage of SDG achievement, with a score of 100 indicating that all SDGs have been achieved.

 

Rate of Progress ("Velocity")
Countries will be progressing towards their SDGs at different rates, which we can think of like the vehicle’s velocity (i.e. speed and direction). To represent the vehicle’s current rate of progress (velocity), the data include a (rough!) estimate of each country’s UNICEF programme results Links to an external site. and the corresponding rate of progress according to the indicators defined in each CPD for tracking progress and performance of UNICEF programme interventions. While the Sustainable Development Report includes trend data for each country’s SDG Index Score (which measures the overall rate of progress/velocity for all programs), the measure provided here only considers UNICEF’s programme interventions (which they have full agency to alter). These are computed as follows:

From all of UNICEF’s 130+ country office Country Programme indicators, Evan took the subset with units that are percentages (roughly 1/3 of all indicators) and therefore on the same numerical scale (unlike indicators with ‘countable units’ like people, districts, or supplies where bounds are unknown).
Evan then used a machine learning model trained on the OSDG dataset Links to an external site. to classify each indicator according to which SDG Goal Area it is most likely to be related to.
For each SDG Goal Area and each country, Evan calculated the difference between each indicator’s initial baseline value and the actual result value (using the target value to determine which direction means progress).
Values for each goal area were then summed and divided by the number of years between the baseline and actual result to produce a ‘velocity’ measure for each SDG Goal Area for each country office.

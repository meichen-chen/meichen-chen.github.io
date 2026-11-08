---
layout: page
permalink: /research/
title: Research
---
## Working Papers

1. **Dirty Trade: How Global Used Vehicle Trade Mediates Clean Transitions (Job Market Paper) (2026)**

   <div class="paper-buttons">
   [<button type="button" class="paper-button" aria-expanded="false" onclick="toggleAbstract(this)">Abstract</button>]
   [<a class="paper-button" href="/Chen_Meichen_JMP.pdf">PDF</a>]
   </div>
   <div class="paper-abstract" hidden>
   Clean vehicle policies can accelerate transitions to greener economies in countries that adopt them, yet displaced used vehicles may enter the global market, with uncertain consequences for emissions and welfare abroad. This paper studies the spillover effects of Japanese Clean Energy Vehicle subsidies from 2013 to 2024 on Uganda, where around 90% of first-time registered passenger vehicles were used imports from Japan. I link Japanese subsidy schedules to data on first-time registrations, prices, and emissions of vehicles in Uganda. Exploiting variation in exposure to subsidies across different vehicles and over time, difference-in-differences estimates suggest the subsidies decreased prices and increased the number of first-time registered vehicles. The effects were concentrated among vehicles aged 6–13 years, which were younger and generally less emissions-intensive than the average first-time registered vehicle in Uganda. To quantify the equilibrium effects of the subsidies on total emissions and welfare, I estimate a model of vehicle demand and supply in Uganda with endogenous inflows and scrappage. Simulations show that the subsidies increase total emissions, as fleet expansion outweighs the reduction in average emissions per kilometer. Nonetheless, gains in consumer surplus lead to an increase in welfare. The subsidies also change the trade-off associated with age-based import restrictions in Uganda. Tightening the import age limit from 15 to 13 years, as recently proposed, lowers total emissions at the cost of consumer surplus. Through lower prices of younger vehicles, the subsidies decrease the resulting emissions savings, as the smaller reduction in the fleet size dominates the larger reduction in average emissions per kilometer. Losses in consumer surplus also decrease, but to a lesser extent. Consequently, the tighter limit reduces welfare under the subsidies, whereas it would have increased welfare in their absence.
   </div>

2. **Measuring the Option Value of Change: Theory and an Application to Operation Ceasefire (2026)**<br />
   with [Sylvain Chassang] and [Michal Kolesár]

   <div class="paper-buttons">
   [<button type="button" class="paper-button" aria-expanded="false" onclick="toggleAbstract(this)">Abstract</button>]
   [<a class="paper-button" href="https://www.sylvainchassang.org/assets/papers/option_value_of_change.pdf">PDF</a>]
   </div>
   <div class="paper-abstract" hidden>
   When treatment effects are heterogeneous across units but auto-correlated over time, there is value to dynamic treatment rules that assign treatment status on the basis of past treatment outcomes. Treatment has an option value. The challenge is that correlation in estimated treatment effects may be driven by correlation in errors rather than correlation in treatment effects. This paper shows how to estimate the value of dynamic assignment rules in observational data, and applies the methodology to Operation Ceasefire, a widely adopted homicide reduction program. Using a newly constructed data-set of adoption events across the US, we argue that programs inspired by Operation Ceasefire generate statistically insignificant reductions in homicide rates on average, but that their effectiveness is significantly improved by dynamic adoption. A naive approach would considerably overestimate these benefits.
   </div>

3. **New-Car Waves, Used-Car Cascades: The Geography of Replacement (2026)**<br />
   with [Nico Lukas Kasparetz]

   <div class="paper-buttons">
   [<button type="button" class="paper-button" aria-expanded="false" onclick="toggleAbstract(this)">Abstract</button>]
   <span class="paper-note">Draft coming soon</span>
   </div>
   <div class="paper-abstract" hidden>
   New vehicle launches can trigger waves of vehicle replacement across countries as displaced vehicles are reallocated through international used-car markets. We study how new vehicle launches in Europe affect vehicle replacement in Germany and Romania, an import-dependent market that sources predominantly from Germany. We combine vehicle-level registration records from both countries with launch schedules in Europe and electric vehicle (EV) subsidy schedules in Germany. Exploiting variation in launch timing and similarity between incumbent and newly introduced vehicles, we find that launches increased new vehicle sales and de-registrations of incumbent vehicles in Germany. In Romania, launches did not increase new vehicle sales. They increased first-time registrations of used vehicles imported from Germany and de-registrations of generally older and more emissions-intensive incumbent vehicles. The effects were substantially larger for EV launches, partly because of EV subsidies in Germany. Ongoing work develops a dynamic model of vehicle replacement in Germany and Romania to evaluate the effects of alternative German EV subsidy designs on emissions and welfare in both countries, including designs that condition subsidies on scrappage and thus prevent displaced vehicles from triggering further waves of replacement abroad.
   </div>
{: .paper-list}

## Work in Progress

1. **The Incidence of Overlapping Environmental Regulations**<br />
   with [Xiang Ma] and [Junming Zhu]

   <div class="paper-buttons">
   [<button type="button" class="paper-button" aria-expanded="false" onclick="toggleAbstract(this)">Abstract</button>]
   </div>
   <div class="paper-abstract" hidden>
   When sector-specific environmental policies operate alongside aggregate emissions targets, additional abatement induced in one sector may reduce the abatement required elsewhere. We examine the incidence of aggregate targets when there are concurrent sector-specific policies. Our setting is China’s Eleventh Five-Year Plan, under which cities faced similar percentage reduction targets for SO₂ emissions alongside substantial abatement requirements for power plants. We find that cities achieved similar proportional reductions in aggregate SO₂ emissions, with smaller reductions among other industrial firms offsetting larger reductions from power plants nearly one-for-one. Greater exposure to power-sector requirements reduced declines in input demand and output among other industrial firms, and the effects varied systematically with firm characteristics. Together, the findings suggest that sector-specific regulations can largely reallocate, rather than increase, aggregate abatement while substantially changing the incidence of compliance.
   </div>

2. **Clean Today, Dirty Tomorrow: Strategic Emissions under Dynamic Environmental Enforcement**<br />
   with [Mengdi Liu], [Bing Zhang], and [Junming Zhu]

3. **Long-Term Contracts, Locked-In Coal, and Energy Transition**<br />
   with [Gabriel Dias Santamarina]
{: .paper-list}

[Sylvain Chassang]: https://www.sylvainchassang.org/
[Michal Kolesár]: https://www.princeton.edu/~mkolesar/
[Nico Lukas Kasparetz]: https://www.uni-mannheim.de/gess/programs/cdse/our-students/2022/nico-kasparetz/
[Xiang Ma]: https://sites.google.com/site/xiangma6
[Junming Zhu]: https://www.sppm.tsinghua.edu.cn/english/info/1067/1940.htm
[Mengdi Liu]: https://liumengdinn.wixsite.com/website
[Bing Zhang]: https://hjxy.nju.edu.cn/English/Faculty/FulltimeTeacher/DepartmentofEnvironmentalPlanningandManagement/Professors/20230404/i242040.html
[Gabriel Dias Santamarina]: https://gabrieldiassantamarina.github.io/

<script>
// Abstract buttons: show or hide the abstract right below the button row.
function toggleAbstract(button) {
  var abstract = button.parentElement.nextElementSibling;
  abstract.hidden = !abstract.hidden;
  button.setAttribute("aria-expanded", String(!abstract.hidden));
}
</script>

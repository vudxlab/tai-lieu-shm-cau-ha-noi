Portland State University 
Portland State University 
PDXScholar 
PDXScholar 

Civil and Environmental Engineering Faculty 
Publications and Presentations 
Civil and Environmental Engineering 

3-1-2025 

Life Safety in the Reliability-Based Design and 
Life Safety in the Reliability-Based Design and 
Assessment of Structures 
Assessment of Structures 

Mahesh Pandey 
University of Waterloo 

Celeste Viljoen 
Stellenbosch University 

Andrew Way 
Stellenbosch University 

Katharina Fischer 
Matrisk GmbH 

Miroslav Sykora 
Czech Technical University in Prague 

See next page for additional authors 

Follow this and additional works at: https://pdxscholar.library.pdx.edu/cengin_fac 

 Part of the Civil and Environmental Engineering Commons 
Let us know how access to this document benefits you. 

Citation Details 
Citation Details 
Pandey, M., Viljoen, C., Way, A., Fischer, K., Sýkora, M., Diamantidis, D., Steenbergen, R. D. J. M., Lind, N., 
Frangopol, D. M., Yang, D. Y., Retief, J. V., André, J., Nathwani, J., & Lenner, R. (2025). Life safety in the 
Reliability-Based design and assessment of structures. Structural Safety, 113, 102453. 

This Article is brought to you for free and open access. It has been accepted for inclusion in Civil and 
Environmental Engineering Faculty Publications and Presentations by an authorized administrator of PDXScholar. 
Please contact us if we can make this document more accessible: pdxscholar@pdx.edu. 


Authors 
Authors 
Mahesh Pandey, Celeste Viljoen, Andrew Way, Katharina Fischer, Miroslav Sykora, Dimitris Diamantidis, 
Raphael D. J. M. Steenbergen, Niels Lind, Dan M. Frangopol, David Y. Yang, and multiple additional authors 

This article is available at PDXScholar: https://pdxscholar.library.pdx.edu/cengin_fac/742 


Structural Safety 113 (2025) 102453

Available online 23 February 2024
0167-4730/© 2024 The Authors. Published by Elsevier Ltd. This is an open access article under the CC BY-NC license (http://creativecommons.org/licenses/by-
nc/4.0/).

Life safety in the Reliability-Based design and assessment of structures 

Mahesh Pandey a, Celeste Viljoen b,*, Andrew Way b, Katharina Fischer c, Miroslav Sýkora d, 
Dimitris Diamantidis e, Rapha¨el D.J.M. Steenbergen f,g, Niels Lind a, Dan M. Frangopol h, 
David Y. Yang i, Johan V. Retief b, Jo˜ao Andr´e j, Jatin Nathwani a, Roman Lenner b,d 

a University of Waterloo, Canada 
b Stellenbosch University, South Africa 
c Matrisk GmbH, Switzerland 
d Czech Technical University in Prague, Czech Republic 
e Ostbayerische Technische Hochschule, Regensburg, Germany 
f TNO Delft, the Netherlands 
g Ghent University, Belgium 
h Lehigh University, USA 
i Portland State University, USA 
j LNEC, Portugal   

A R T I C L E  I N F O   

Keywords: 
Life safety 
Structural assessment 
Standardization 
Reliability-based design 
Risk-informed design 

A B S T R A C T   

We review the developments in life safety and the incorporation thereof in the design and assessment of 
structures over the last 50 years. Various measures of life safety are presented that have been developed ac­
cording to the marginal life saving cost principle based on individual, societal and economic considerations. 
Target probabilities of failure, or target reliabilities, are central to modern structural design and assessment. 
These are derived either through back-calibration to existing practice or through life cycle cost minimisation, 
both of which yield comparable safety levels, and are underpinned by lower bounds from life safety. Life cycle 
cost minimisation is reviewed here, which considers all direct and indirect costs of failure including loss of life 
and limb, as well as the costs and efficiency of increasing reliability. We discuss the incorporation of life safety 
into reliability-based design and assessment through the concept of the Life Quality Index, which uses key so­
cietal indicators, namely, the GDP and life expectancy, and health economics as a basis for specifying minimum 
reliabilities for both new and existing structures. The current state of advancement of reliability- and risk- 
informed design, and recommendations for future developments in life safety are considered.   

1. Introduction 

Accounting for life safety in reliability-based design of structures 
demonstrates the progress made over the past decades of advancing the 
rational basis and subsequent level of performance of structures in 
design practices. During the initial stages of implementing reliability 
methodologies into structural design practices, provision for life safety 
was imbedded in target levels of reliability derived from back calcula­
tion of acceptable practice. As economic optimisation gained preva­
lence, it proved to be an effective way of determining target levels of 
reliability. To ensure that the economically optimal and feasible de­
cisions are also coherent with the societal preferences for health and life 
safety, complementary socioeconomic (societal) metrics and approaches 

were explored [1]. The trajectory of the development of a rational basis 
for accounting for life safety and its integration into the reliability and 
decision-making basis for the design and assessment of structures is 
critically reviewed in this paper. 
Life safety remains one of the primary building blocks upon which 
modern structural risk-informed design is built. In its simplest form, a 
structure needs to be designed such that it is fit for purpose, is safe and 
robust [1] and remains resilient over its design lifetime. The term “safe 
structure” in structural engineering is somewhat ambiguous though and 
requires qualification. Designing a structure where human life safety is 
never endangered - as a philosophical premise - is physically impossible 
to implement due to uncertainties and unknowns in the resistance and/ 
or loading of the structure [2]. The term “safe structure” should 

* Corresponding author at: Stellenbosch University, Department of Civil Engineering, Banhoek Road, Stellenbosch, 7600, South Africa. 
E-mail address: Celesteviljoen@sun.ac.za (C. Viljoen).  

Contents lists available at ScienceDirect 

Structural Safety 

journal homepage: www.elsevier.com/locate/strusafe 

https://doi.org/10.1016/j.strusafe.2024.102453 
Received 30 September 2023; Received in revised form 1 February 2024; Accepted 19 February 2024   


Structural Safety 113 (2025) 102453

2

therefore be interpreted as implying a judgement on the “engineered 
safety design” which results in the realization of a structure for which 
the probability of a loss of life (casualty) is acceptably low throughout its 
design life. 
An important consideration then follows logically: What then is an 
acceptably low probability of failure resulting in deaths? Or as more 
commonly phrased: How safe is safe enough when considering life 
safety? The mirage of absolute safety is confronted by the limits of a 
society’s economic capacity to achieve various goals. Given the impos­
sibility of achieving absolute safety and that there is a limited budget for 
improving the overall life quality of all citizens, investments into life 
safety are further constrained with respect to the level of “safety” that is 
practically achievable [3]. In addition to financial constraints, the de­
gree to which a society avoids risk to life also affects what risks it con­
siders acceptable; one society may accept risks which another may 
consider unacceptable [4]. The societal capacity to commit resources 
differs across various jurisdictions and each country has unique budget 
allocations for investment into life safety. As a result of the above, in 
most cases, an acceptable probability of casualty is also specific to each 
society. 
Advancements in the incorporation of life safety in structural design 
over the last 50 years have been proposed and various methods devel­
oped to incorporate life safety into the design of structures. Some of 
these methods define, more explicitly, a probability of casualty in the 
event of structural failure, based on the probability of casualty for other 
events in everyday life, or through an aversion to cases where mass 
casualties may ensue from structural failure. The individual and societal 
risk criteria are examples of these more explicitly defined limits. Other 
methods prescribe measures whereby a society’s capacity to commit 
resources to avert a casualty is used as a basis for minimum levels of life 
safety to be specified, such as the use of the Life Quality Index [5]. The 
Marginal Life Saving Cost (MLSC) principle is an overarching approach 
used to link acceptance criteria for risk to life to the resources available 
to improve human safety. 
In conjunction with life safety requirements, economic feasibility 
also plays a notable role in part of the design process. A balance must be 
achieved between resource provision for the promotion of life safety, 
and that which can be afforded by a society [6,7]. Economic cost opti­
misation can therefore be used to specify optimal probabilities of failure 
for a given reference period from an investment perspective. As a means 
of ensuring that life safety is not neglected for the sake of economy in life 
cycle cost minimisation, various methods have been proposed that 
incorporate the individual, societal or Life Quality Index (LQI) as lower 
bound criteria on target reliability values determined from economic 
optimisation, although these seldom govern the design of new struc­
tures. As such, target reliability values in modern reliability-based 
design codes are typically determined by either economic optimisa­
tion, back-calibration to existing practice or a combination of the two. 
As many structures across the U.S.A, Europe and other developed 
regions are, or will soon be reaching the end of their design life, there is 
an increasing interest in target reliability levels in existing structures. 
Repurposing and retrofitting existing structures are sometimes a viable 
alternative to demolition and reconstruction. Given the fact that the cost 
of increasing safety levels in existing structures is typically notably 
higher than in new structures, lower reliability levels result from eco­
nomic optimisations [8,9]. As a result, lower bounds from life safety 
requirements often govern the reliability of existing structures, espe­
cially those with a short remaining service life [10]. It should be noted 
that the target reliability levels, and the actual failure probability rates 
are unlikely to correspond directly, though they should be similar [11]. 
The calibration of reliability-based design codes aims to achieve 
target reliability through the choice of load factors, load combinations 
and material partial factors (or resistance reduction factors in the load 
and resistance factor design format). Despite a large body of research on 
target reliability optimization, most of the currently used reliability- 
based structural design codes are not based on an explicit 

optimization of either life cycle cost or life safety goals. Rather, partial 
factors used in these codes were calibrated to target reliability levels 
implied by codes of previous generations. However, the partial factors 
are revised over time with an increasing understanding of the mechanics 
of failures. 
This article serves to review the developments of the inclusion of life 
safety in structural design over the last 50 years. Notable contributions 
made towards life safety in structural design and subsequently risk- 
informed design are reviewed, and challenges that remain in current 
forms of life safety inclusion in structural design are discussed. 

2. Measures of life safety and application to structural design 

Currently, the As-Low-As-Reasonably-Practicable (ALARP) frame­
work, which has its origins in the United Kingdom Health and Safety at 
Work etc. Act of 1974, is typically used as the regulatory framework for 
life safety risk acceptance in structural design [1,12]. Within this 
framework, risk to individuals and society while using/occupying 
structures are classified as being broadly acceptable, tolerable, ALARP, 
or intolerable, as illustrated in Fig. 1. Broadly acceptable risks are not 
required to be optimised to be as low as possible, whereas intolerable 
risks are those that cannot be accepted other than in exceptional cir­
cumstances. Most structures fall into the ALARP risk range, where risks 
are moderate to high. In this range, risks to life are only acceptable when 
they are optimised to be ALARP i.e., where further risk reduction is 
impractical or is notably disproportionate to the increase in safety 
gained or decrease in the failure costs [13]. 
Life safety measures in structural design can be specified from an 
individual risk, a societal risk, and an economic perspective. 

2.1. Individual Risk 

Individual risk criteria have arisen from the notion that when using a 
structure, across a society, individuals should not be exposed to risks 
that are greater than those associated with everyday life [13]. These 
risks of death in everyday life are typically expressed in terms of the 
probability of death, per time period (usually one year). Faber et al. [2] 
suggest the use of the fatality rate instead, which is defined as the ratio 
between the expected value of the number of lost lives per annum and 
the expected number of person years per annum during which in­
dividuals are exposed to a specific risk. For small probabilities, this 
metric is numerically equivalent to the probability of death for a sta­
tistical, rather than a specific individual. Various research has reported 
acceptable values for individual risk: a small sample is shown in Table 1 
for illustration, while a more comprehensive list of examples is given in 
[13]. 
From as early as 1966, in work by Freudenthal et al. [18], proposals 
for an absolute maximum acceptable probability of death from struc­
tural failure in the order of 10−5 to 10−6 were made. A general consensus 

Fig. 1. Illustration of the ALARP principle, adapted from [14].  

M. Pandey et al.                                                                                                                                                                                                                                


Structural Safety 113 (2025) 102453

3

has been reached that this range is indeed reasonable as a threshold for 
the 
acceptable 
risk 
region 
of 
the 
ALARP 
framework 
[7,13,17,19,20,21,22,23,24]. The range for individual risk is intended 
to be an absolute lower bound to safeguard individuals from being 
exposed to unacceptable risks that may be proposed by cost optimisa­
tion, even though these risk levels may result in maximum utility or 
lowest cost (see section 3.1). These values relate to the probability of 
death, given structural failure, Pd|f, and not simply to the annual prob­
ability of structural failure, Pf. The resulting probability of death, Pd, is 
thus the product of the probability of structural failure, and the proba­
bility of death given structural failure, as shown in Equation (1), if an 
annual a value of 10−5 is accepted. 

Pd = Pf ⋅Pd|f < 10−5
(1)  

While the notion is simple, notable complexity is involved in deter­
mining Pf and Pd|f, both due to the wide variety of structures that exist, 
as well as because of the inter-dependence between individual structural 
member failure and structural system failure, alternative load paths and 
redundancy. The requirement for structural failure from individual risk 
criterion is shown in Equation (2). 

Pft,IR ≤10−5

Pd|f

(2)  

From this basis, through the determination of Pd|f, a set of target struc­
tural failure probabilities can be defined. The Pd|f is complex to gener­
alize and will vary depending on the structure, its intended use, and the 
consequences if structural failure occurs. Over time most modern codes 
have therefore introduced the concept of a consequence class for each 
structure or group of structures; the nomenclature of EN 1990 [19] is 
used here. Consequence classes CC1, CC2 and CC3 are used to differ­
entiate between structures that have low, medium and high qualitative 
consequences of failure, respectively. 
Given these consequence classes, fib Bulletin 80 [25] proposes 
tentative Pd|f values based on Eldukair & Ayyub [26], Steenbergen & 
Vrouwenvelder [17] and EN 1990 [19], as shown in Table 2, based on 
the qualitative definition of the consequence classes. Subsequent annual 
target probabilities of structural failure based on individual risk are 
posed as a function of consequence class, specifically for buildings. As 
the duration of time any individual spends at risk on or around a bridge 
is notably small, individual risk criteria are not typically applied to 
bridges. The argument of spending just short periods in specific situa­
tions, however, should be handled with care. In the course of time, 
people may be present at a sequential set of risk generating situations, in 
which case one should not use a reduction because of a short stay per 
situation. See [3] for further discussion. 

In ASCE 7–22 [27], a structure is classified into one of 4 categories 
based on the risk to human life and welfare resulting from their damage 
or failure, as shown in Table 4a. The target annual probabilities of 
failure for these risk categories vary from 10−4 to 10−7 per year. 
In the seismic design and assessment of structures, an explicit use of 
life safety as a performance measure is starting to become prevalent. The 
target reliability levels specified in ASCE7-22 are such that new struc­
tures designed in Risk Categories II through IV would pose a very low 
risk to life. However, this is not necessarily true for many existing 
buildings, i.e., they will not provide the level of life safety protection 
expected of new buildings designed according to ASCE 7–22. Therefore, 
the protection of life often becomes a primary objective of seismic up­
grade projects. FEMA [28] specifies the casualty rate as a measure of life 
safety, which is defined as the probability of any one occupant in a 
building being fatally or seriously injured during an earthquake. Under 
the design earthquake, the target conditional casualty rate is specified as 
0.01 and 0.005 for Risk Categories II and IV, respectively [28]. A more a 
detailed account of historical developments related to life safety con­
siderations in the performance-based seismic design of structures is 
presented in Krawinkler and Miranda [29]. 

2.2. Societal risk 

Societal risk criteria are based on the principle that society is less 
tolerant of isolated events with larger consequences of failure than it is 
of numerous smaller events with equivalent cumulative consequences. 
However, there has been considerable debate about the concept of risk 
aversion when used in the context of normative decision-making and it 
is deemed problematic. 
Group risk criteria are often given in the form of frequency- 
consequence curves, also known as F-n curves, which were initially 
developed for risks related to the siting of nuclear facilities in Farmer 
[30]. F-n curves are most generically defined by Equation (3), where Nf 
is the number of casualties in one event, in one year [13,25]. 

Pf < AN −α

f
(3)  

The A term represents the frequency of occurrence of an event with at 
least one casualty. The α term describes what is referred to as risk 
aversion i.e., the degree to which a society is risk averse. Values for α 
typically range from 1 to 2, where 1 is associated with a society which is 
negligibly risk-averse and 1 < α for an increasingly risk-averse society. A 
value of α = 2 is typically used [13,15]. However, some argue that all 
societies are risk-adverse to some extent, so values of α < 2 should also 
be considered [10]. When applying Equation (3) to structural reliability, 
the A constant takes the value of 0.01 to 0.1 for groups of structures. 
However, for practical applications, group risk is most often specified 
based on failure of a single structural member and the value for A needs 
to be adjusted, see Tanner & Hingorani [31,32] and fib Bulletin 80 for a 
more in-depth consideration of societal risk criteria. 
The use of societal risk criteria has been debated in literature. There 
are strong arguments against the use of F-n curves for risk acceptance, 
even with a “risk neutral” α value of 1 [33,34], while others suggest that 
F-n curves are compatible with classical decision theory [35]. Further 
discussions and cautions on the use of societal risk criteria for risk 
acceptance in normative decision-making are presented in Section 4.1. 

2.3. Life Quality Index (LQI) 

A more explicit consideration of life safety and risk management in 
structural design is based on the use of the marginal life saving costs 
(MLSC) principle aiming at an efficient use of societal resources to 
reduce various risks to life (see also Section 3.2). In the field of structural 
reliability, the MLSC principle has found its implementation using the 
formulation of the LQI, which finds its basis in key societal indicators 
and health economics. In a broader context of life safety and risk 

Table 1 
Annual probability of death for various everyday cases.  

Pd 
Note 
Reference 

10−4 
Lethal accident rate 
ISO 2394:1998 [14] 

10−3 
Natural causes for developed countries, 
people under 60 
Vrouwenvelder et al. [15] 

10−3 
Basic risk level (UK) 
CIRIA [16] 

10−4 
Accidental death (Netherlands) 
Steenbergen & 
Vrouwenvelder [17]  

Table 2 
Proposed Pd|f and Pft,IR for buildings from fib Bulletin 80.  

Consequence 
Class 
Probability of death, given 
failure (Pd|f) 
Annual target probability of 
failure (Pft,IR) 

CC1  
0.01 
Pft,IR ≤1 × 10−3 

CC2  
0.05 
Pft,IR ≤2 × 10−4 

CC3  
0.20 
Pft,IR ≤5 × 10−5  

M. Pandey et al.                                                                                                                                                                                                                                


Structural Safety 113 (2025) 102453

4

management, Lind et al. [36] formulated a fundamental principle which 
extends to all risks to the public that are managed by professionals or by 
regulations: Risk should be managed such as to maximize the net benefit 
to society. They further proposed that Quality-Adjusted Life Years 
(QALYs), a measure combining the length and quality of life, be the 
measure of benefit to life and health of all risk mitigation efforts. 
Risk management, in addition to life risk, also involves finance: costs 
and economic risk, measured in some monetary currency, e.g. dollars. 
This raises a question fundamental to risk management: How are QALYs 
and dollars to be compared? What is the value of a dollar in terms of the 
length and quality of human life? Lind et al. [36] asserts that what 
fundamentally matters in life are how long one lives, and the level of 
resources one can command to enjoy and improve the total quality of 
one’s life. Although a simplification of a more complex set of trade-offs, 
the latter can be seen as true in an overall sense for any society as a 
whole. This notion led to the Life Product Indicator (LPI), a two- 
dimensional function of life expectancy at birth (e) and the gross do­
mestic product (g) per person per year, for a specific society. Nathwani 
et al. [5] expanded the idea of risk management in public interest 
introduced in [36] and formulated the Life Quality Index as a foundation 
of a more structured approach for maximizing net benefit to society. 
Pandey et al. [37] presented an adaptation of the LQI as a lifetime 
utility enjoyed by a statistically representative person in a society. This 
approach was inspired by a utility principle proposed by Samuelson [38] 
in developing a framework for measuring marginal utility of income: 
“During any specified period of time, the individual behaves so as to 
maximise the sum of all future utilities”. Thus, assuming a utility func­
tion of consumption as gq, the total utility over an uncertain remaining 
lifetime, T, can be simply written as L = gqT. Here, q is dependent on the 
ratio of average work to leisure times available to members of society 
and accounts for the fact that a part of the GDP is realized through work 
and the other part through returns on investments. Thus, the expected 
value of the total lifetime utility is equivalent to the LQI, i.e., 

L = E[gqT] = gqE[T] = gqe
(4)  

The life expectancy at birth, e, is used for the sake of a standardized 
definition. In a general setting, it can be treated as the remaining life 
expectancy of any age group exposed to risks. Using economic data from 
developed economies of OECD (Organization of Economic Cooperation 
and Development) countries, an estimate of q = 0.2 was proposed [37]. 
The LQI was proposed as a practical tool to assess whether a project, 
policy, regulation, or practice confers a positive net benefit in compar­
ison with an alternative that can be labelled status quo. Any project or 
regulation that materially affects the public by risk and expenditure will 
have an impact on corresponding indicators, life expectancy and the 
GDP, respectively. Using Equation (4), a small change in LQI, dL, in 
terms of small, finite changes in the GDP, dg, and life expectancy, de, can 
be expressed as: 

dL
L = q dg
g + de
e
(5)  

The net benefit criterion requires that dL ≥0. Given a prospect of 
increased risk, Pandey and Nathwani [39] defined the Societal Capacity 
to Commit Resources (SCCR), also known as the societal willingness to 
pay, for a risk reduction program as the minimum income that the so­
ciety is willing to commit to reduce the risk (i.e., increase the life ex­
pectancy) by such a magnitude that the net change (or reduction) in LQI 
is zero. Using Equation (5), the LQI invariance condition can be written 
as: 

dL
L = q dg
g + de
e = 0
(6)  

Which leads to the SCCR, GΔ, (in $/person/year) as: 

dg = −GΔ = −g
q

de
e
(7)  

The SCCR can also be interpreted as a monetary equivalent of a gain in 
life expectancy from a risk reduction program, or equivalent monetary 
loss in the program’s absence. Rackwitz [6] defined the implied cost of 
averting a fatality (ICAF) from Equation (7) as dg⋅e = gde/q. Rackwitz 
[6] further proposed to incorporate dL/L ≥0 as a constraint in the life 
cycle cost optimisation problem, which was widely used in subsequent 
studies as discussed in the next section. Nathwani et al. [4] proposed the 
SCCR to a risk management program as −dg/de = g/qe. Alternate ways 
of estimating q are discussed in Lind [40]. 
The LQI invariance condition, Equation (4), has been widely used to 
link life safety objectives with the economic efficiency of a risk man­
agement program. In Rackwitz [6], for example, Equation (4) is pro­
posed as an additional constraint in the life cycle cost optimisation, 
which made it possible to incorporate life safety goals into structural 
design practice in a well-defined manner, as discussed in Section 3.2. 

2.4. Link between life safety and structural reliability 

Until the late 1960′s, design methods were typically based on 
ensuring a global factor of safety given by the ratio of the resistance or 
allowable stress to the applied expected maximum load, rather than 
explicit life safety or reliability targets. In the previous sections, a link 
was made between the probability of death, Pd, the probability of 
structural failure, Pf, and the probability of death given structural fail­
ure, Pd|f, as shown in Equation (1) for a specified time period (annual/ 
lifetime etc.). Based on this relationship, the probability of structural 
failure, Pf, (or a derivative of it, as discussed further on) is typically used 
in modern day design codes. 
Further to the use of Pf, a move towards the notion of probability of 
survival, or structural reliability in design was initially proposed by 
Freudenthal et al. [18], as an alternative to the traditional factor of 
safety method. While the concept of reliability and probabilistic 
methods were initially overlooked, perhaps due to their complexity, the 
lack of widely available computational resources at the time, or simply 
because they required a significant change from the existing design 
philosophy, it now forms the basis of modern design. Additional notable 
research by Ellingwood & Galambos [41], Cornell [42], Ditlevsen [43], 
Rosenblueth & Mendoza [44] and Hasofer & Lind [45] amongst many 
others, as well as the formation of the Joint Committee on Structural 
Safety (JCSS) and the JCSS PMC [7] contributed to the initial and sub­
sequent implementation of reliability in structural design. 
The concept of a reliability index, β, was introduced by Cornell [46] 
and later refined by Hasofer & Lind [45], which is directly linked to the 
probability of failure, as a measure of the reliability of a structure or 
structural member. The reliability index is given as the probability that 
the value of a limit state function, G, is less than zero. A limit state 
function is typically defined by the difference between some generic 
structural resistance, R, that is dependent on a decision parameter, d, 
and a load or action effect, S, as shown in Equation (8). In some cases, 
the load effect may also be dependent on the decision parameter, 
however, in most cases it is assumed to be negligibly dependent on it. 
The notion of reliability also incorporates a probabilistic consideration 
of both R and S. Most modern design codes use the reliability index as a 
means by which to specify the desired (target) level of reliability, as well 
as a surrogate for life safety, either directly or indirectly. 

Pf = P(G(d) < 0) = P(R(d) −S < 0) = Φ( −β)
(8)  

To achieve these desired levels of structural reliability, while semi- 
probabilistically considering resistance and load, the partial factor 
design method (also called load and resistance factor design - LRFD) was 
developed as a so-called level I or semi-probabilistic method [19,47,48] 
and is still widely used today. The method already had its origins in work 

M. Pandey et al.                                                                                                                                                                                                                                


Structural Safety 113 (2025) 102453

5

by Ferry-Borges & Castanheta [49] and the committee for ACI Standard 
318–63, as reported by Ellingwood [50] but did not gain popularity until 
the late 1970′s and early 1980′s when codes started the process of 
adopting at least a semi-probabilistic consideration of resistance and 
load in e.g., Ravindra & Galambos [51], Ellingwood [52] and K¨onig & 
Hosser [47]. The Eurocodes, Model Code 2010 [53], ASCE 7 [27] and 
ACI 318 [54] are all prominent examples of such semi-probabilistic 
design codes. As the basis of design, these codes specify target reli­
ability levels for structures, depending on the consequence class and in 
some cases, additionally the cost of increasing safety. The calibration of 
design codes to achieve the target reliability is discussed in Sørensen, 
et al. [55]. 
While individual and group risk criteria are lower bounds placed on 
life safety levels, whether defined by a probability of failure or reliability 
index, the target reliability of new structures is typically governed by 
economic considerations, which usually requires a higher level of reli­
ability than life safety requirements. Economic considerations also 
govern structures where there is no risk of life being endangered. Recent 
developments in economic cost optimisation further resulted in the 
incorporation of life safety directly into reliability-based design (RBD), 
as discussed in the following section. 

3. Reliability-based design by economic optimisation & life 
safety 

Structural design is safeguarded by life safety requirements but, of 
course, is also notably constrained by the cost of a structure. As such, the 
structural cost is to be minimized while acceptable life safety levels must 
be achieved. The structural design of new structures is typically gov­
erned by economic optimisation either implicitly through back- 
calibration to existing practice or explicitly as discussed in the following. 

3.1. Reliability-based design by economic optimisation 

RBD by economic cost optimisation is based on the maximization of 
the utility or more frequently, due to the difficulty in monetizing utility, 
the minimization of the life cycle cost of a structure. While the notion of 
cost minimization has existed in some shape or form long before the 
2000′s (e.g. Starr [56]), one of the first definitive cost optimisation 
frameworks aimed at determining target reliability for overarching 
structural design standardization purposes was proposed by Rackwitz 
[57], based on research by Mendoza & Rosenblueth [58] and Rose­
nblueth [59]. The optimisation seeks to minimize the total life cycle cost 
as a function of some decision parameter, d, which most efficiently in­
creases the structural reliability (or lowers the probability of failure). 
The optimisation relates to a defined failure event, be it on a component 
or system level. The safety costs and failure consequences as well as the 
models used to estimate the probability of failure must therefore relate 
to the same failure event. At system level such assessment needs to ac­
count for structural robustness. A detailed discussion may be found in 
Fischer et al. [60]. Examples of d include section or material properties, 
loading parameters, type of structural system, etc. Reliability levels in 
codes and standards typically apply to a single failure mode at compo­
nent level caused by a dominating combination of load effects. Equation 
(9) represents the limit state for a member that governs structural failure 
and includes a probabilistic formulation of resistance (R) and load (S), 
both as a function of d (though S is often independent of d). The opti­
misation incorporates the effect of changes in the decision parameter 
both in terms of cost and reliability, through the probability of failure. 
The process therefore aims to find an optimal choice of d to minimize the 
total cost of the structure or member, Z(d), as shown in Fig. 2 and 
explained further below. 
A general form of the total cost is given by Equation (10), where C(d),
A(d) and D(d) are the construction, demolition, and ultimate limit state 
(ULS) failure costs, respectively, associated with either a member or 
structure. Other costs may also be included, e.g. those related to 

inspection and maintenance and serviceability limit state (SLS) failures; 
however, the latter are often neglected for typical structures [57]. 
Equation (11) gives a more detailed quantification of the total costs 
normalized by the part of the fixed initial cost of the structure, C0, that is 
independent of the decision parameter. 

G(d) = R(d) −S(d)
(9)  

Z(d) = C(d) + A(d) + D(d)
(10)  

z(d) =
(
1 + C1

C0

⋅d
)
⏞̅̅̅̅̅̅̅̅⏟⏟̅̅̅̅̅̅̅̅⏞

C(d)/C0

+
(
1 + C1

C0

⋅d + A
C0

)
⋅ω

γ

⏞̅̅̅̅̅̅̅̅̅̅̅̅̅̅̅̅⏟⏟̅̅̅̅̅̅̅̅̅̅̅̅̅̅̅̅⏞

A(d)/C0

+
(
1 + C1

C0

⋅d + H
C0

)
⋅Pf,ULS(d)
γ

⏞̅̅̅̅̅̅̅̅̅̅̅̅̅̅̅̅̅̅̅̅̅̅̅⏟⏟̅̅̅̅̅̅̅̅̅̅̅̅̅̅̅̅̅̅̅̅̅̅̅⏞

D(d)/C0

(11)  

where: 

C1 Cost related to increasing the decision parameter C(d) = C0 + C1d 
A Costs due to demolition and clearing at end of life. 
H ULS failure costs (excluding reconstruction costs C0 + C1d). 
ω Obsolescence rate. 
γ Age-averaged societal discount rate. 
Pf,ULS(d) Actual annual ULS probability of failure as a function of d, 
from Equation (8). 

The total cost equation can be simulated by a renewal theoretic 
process with an infinite time horizon, assuming that structures are 
continuously rebuilt after each failure or obsolescence event. Costs 
incurred as a result of future events are discounted back to current costs 
using the approximation 1/γ for an infinite time horizon. The γ term is 
the age-averaged annual societal discount rate, which is typically 
assumed to be close to long-term economic growth ≈3% for developed 
countries [61] and ≈8% for developing countries (see Rackwitz [61] 
and Lee & Ellingwood [62] for further discussion on discounting). The 
obsolescence rate, ω, characterizes the annual probability that the 
structure becomes obsolete before the end of its intended design life. It is 
modelled as a Poisson process but is usually approximated as 1/to, where 
to is the expected value of the time to obsolescence. The rate is depen­
dent on a several factors, including structure location, environment, use 
and the level of societal development; values are typically in the range of 
ω = 0.01 −0.02 [63]. The optimisation is notably dependent on the 
marginal cost of increasing safety in the structure (C1/C0) and the ULS 
consequences of failure CF = (1 + d⋅C1/C0 + H/C0). It should be noted 
when C1/C0 ≪C0, that H/C0 corresponds to ρ −1, with a typical range 
of 0 ≤H/C0 < 9, considering the consequences of failure given in 
Table 4a [60]. When the consequences of failure are notably high for 
structures (i.e. when 9 < H/C0) a full cost-benefit analysis, including a 
consideration of life safety, should be conducted to determine appro­
priate levels of target reliability. Costs of increasing safety are given 

Fig. 2. Illustration of optimal choice of decision parameter from cost optimi­
sation. C(d) and D(d) refer to the construction, and ultimate limit state (ULS) 
failure costs, respectively. 

M. Pandey et al.                                                                                                                                                                                                                                


Structural Safety 113 (2025) 102453

6

qualitatively as high, normal and low in the JCSS PMC. Using the JCSS 
PMC/Rackwitz [57] recommendations as a basis, Fischer et al. [60] back 
calculated the costs of increasing safety, yielding the following quanti­
tative ranges for costs of safety. The middle of each range is typically 
used as a representative value.  

Low:
10−4 ≤C1/C0 < 10−3 

Normal:
10−3 ≤C1/C0 < 10−2 

High:
10−2 ≤C1/C0 < 10−1  

When considering the consequences of failure (D(d) in Equation 
(11)), the consequences classes need to be defined quantitatively. 
Consequence classes 1 to 3 are defined on a structural level in Table 3, 
based on the ratio of the economic consequences of failure (CF) to the 
initial cost of the structure (C0), as given in the JCSS PMC. 
The progression of research into RBD by economic optimisation has 
resulted in an over-arching set of recommended target reliability levels 
for new structures. Modern design codes and standards specify target 
reliability values based on the consequences of failure [19,27,53,64], 
but often also as a function of the cost of increasing safety [1,7,65]. 
Table 4b illustrates the annual target reliability as a function of both the 
consequences of failure and the cost of safety, from the JCSS PMC and 
ISO 2394:2015 for new structures; most codes specify the same target 
reliability values or similar values, adjusted to that national context. The 
reliability levels provided in Table 4b are considered comparable with 
those provided in the Eurocodes and other international standards. 

Reliability levels in the standards typically apply to a single failure mode 
at an element level caused by a dominating combination of load effects. 
As before, it should be noted that these values do not consider human 
error and should therefore not be considered as actual failure proba­
bilities. These reliability targets are used as the basis of design, from 
which partial load and material factors are derived. 
When choosing a target reliability from Table 4b, the assessment of 
safety costs and consequences of failure must relate to the same failure 
event. In the original formulation by Rackwitz [57], the ratio C1/C0 
relates to the limit state function in Equation (9) through d, which is 
most intuitively applied for a dominant failure mode addressed during 
the design of a section, structural component or structural unit such as 
frames that represent subsystems of the overall structure (normally ULS 
and the most unfavourable load combination). 
In general, the assessment of the (relative) consequences of failure 
must therefore account for the effect of structural robustness, which 
justifies the range 0 ≤H/C0 < 9 covered by Table 4b for typical struc­
tures. More generally speaking, the reciprocal value of the consequence 
ratio ρ ≈H/C0 +1 is equivalent to the index of robustness IR as defined 
by Baker et al. [66] or, more precisely, to the (conditional) index of 
robustness of the system with respect to the considered failure mode 
scenario [67]. Here, Rdir corresponds to the direct risk associated with 
the failure of a structural element and the denominator represents the 
total risk, including the indirect risk component Rind, see Fischer et al. 
[60] and Faber et al. [68] for details and discussion. 

IR =
Rdir
Rdir + Rind

=
C(d)
C(d) + H = 1

ρ
(12)  

The target reliability proposals in Table 4b constitute a considerable 
advancement in RBD, however, these values only represent what is 
optimal from an economic perspective. Even so, for most new structures, 
the proposals in Table 4b are sufficient to ensure that life safety re­
quirements from an individual and group risk perspective are also 
satisfied. While using economic optimisation, however, there is a 
requirement to link or estimate the monetary value associated with 
human injury and/or the loss human life in the case of failure (within 
H/C0). 

3.2. Incorporation of life safety into RBD using the MLSC and LQI 

To address concerns about attaching a value to human life and to 
safeguard against exposing people to cost optimal decisions that are 
associated with intolerable risks, the MLSC principle can be used. The 
MLSC principle aims to efficiently and equitably distribute societal re­
sources to promote public safety, in the prevention of fatalities or injury 
from structural failure [69]. The ultimate goal is to save as many lives or 
life years as possible, given the societal economic constraints and ca­
pacity to commit resources towards life safety. Following the ALARP 
principle, an investment into safety in a structure (marginal life-saving 
cost) must be made that is at least equal to the minimum income soci­
ety is willing to pay to save an anonymous statistical life, which is 
synonymous with the SCCR [60]. Any cost optimal reliability value that 
is greater than that derived from this value of SCCR is acceptable from a 
risk-acceptance perspective. 
In an application of the LQI to RBD, often referred to as risk-informed 
design, the calculation of the SCCR for small mortality reductions in 
Equation (13) considers a demographical constant, CΔ = de/e, which 
uses age averaged discounting uniformly distributed over all age groups, 
as is appropriate for use across a society, see Rackwitz [61] for details 
related to CΔ. The SCCR is thus unique to each society (or country) and 
should be determined for each; GΔ values for a selection of countries are 
given in ISO 2394:2015 and Rackwitz [61], corresponding to the SCCR 
for saving an additional life. A framework for the application of the LQI 
and SCCR to structural design, in conjunction with economic optimisa­
tion was initially discussed by Rackwitz [6] and subsequently clarified 

Table 3 
Details of consequence classes.  

Class 
Consequences 

Qualitative 
Quantitative ρ =
CF/C0 

CC1 
Low consequence for loss of human life, and 
economic, social or environmental consequences 
small or negligible. 

ρ < 2 

CC2 
Medium consequence for loss of human life, 
economic, social or environmental consequences 
considerable. 

2 ≤ρ < 5 

CC3 
High consequence for loss of human life, or 
economic, social or environmental consequences 
very great. 

5 ≤ρ < 10  

Table 4a 
Risk categories defined in Table 1.5.1 of ASCE 7–22.  

Use or Occupancy of Structure 
Risk 
Category 

Low risk to human life in the event of failure 
I 
All structures except those listed in Risk categories I, III and IV 
II  
(i) Failures could pose a substantial risk to human life, 
Failures with potential to cause a substantial economic impact 
and mass disruption of day-to-day civilian life, 
Facilities dealing with hazardous substance with quantity 
exceeding above a threshold 

III 

Structures designated as essential facilities 
IV  

Table 4b 
Annual target reliability (βt,1) for new structures from cost optimisation, from 
the JCSS PMC.   

Consequences of failure* 

Cost of increasing safety 
Low (CC1) 
H/C0 < 1 
Medium (CC2) 
1 ≤H/C0 < 4 
High (CC3) 
5 ≤H/C0 < 10 

High (C1/C0 ≈5 × 10−2)
3.1 
3.3 
3.7 

Normal (C1/C0 ≈5 × 10−3)
3.3 
4.2 
4.4 

Low (C1/C0 ≈5 × 10−4)
3.7 
4.4 
4.7 

*Note that H0/C0 ≈ρ −1  

M. Pandey et al.                                                                                                                                                                                                                                


Structural Safety 113 (2025) 102453

7

and implemented in Faber & Virguez-Rodriguez [70], Fischer et al. [71] 
and Fischer et al. [60], as shown in Equation (14). The use of LQI in 
conjunction with risk-informed design has also been applied to optimal 
decision making in fire safety by Van Coile et al. [72]. 

GΔ = g
q ⋅CΔ
(13)  

−∂Pf,ULS(d)

∂d
≤C1(γ + ω )
GΔ ⋅Nf

= K1
(14)  

The left-hand side of Equation (14) is understood as the negative of the 
efficiency of the decision parameter, d, at increasing safety [73] and is 
dependent on the form of the decision parameter in the associated limit 
state [74]. The right-hand side is interpreted as the (relative) marginal 
lifesaving cost (K1) that is to be invested for a unit increment in d. The 
SCCR (GΔ) in the denominator of this ratio is multiplied by the expected 
number of fatalities given failure, Nf, as a means of monetizing the 
human consequences of failure in a societally acceptable manner [60]. 
The denominator on the right-hand side only considers the conse­
quences for human life (part of H), so that societal decisions made by it 
are impartial to any economic benefit from the potential reduction in 
material or indirect costs (the rest of H) – see [1] and [71] for discussion. 
The rest of the parameters are as described in section 3.1. It can be seen 
from the marginal lifesaving costs that as the cost to increase safety 
become prohibitively large, the acceptable reliability βt decreases. 
Conversely, when the consequences for human life given failure in­
crease, the allowable βt increases, as illustrated in Fig. 3. 
From this, Fischer et al. [60] propose minimum acceptable reliability 
values as a function of marginal lifesaving costs, shown in Table 5. In the 
determination of K1 values for buildings and bridges, Nf can be estimate 
based on collapsed floor area and bridge span length, respectively. It 
should be noted here that the values in Table 5 can be used at either 
component or system level, if safety costs and failure consequences as 
well as the model used to estimate the probability of failure all relate to 
the same failure event. Caution should be taken when comparing the βt,1 
values in Table 5 with those from Table 4b, as the cost of increasing 
safety is not equivalent to the K1 value from Equation (14). There will be 
a correlation between the two, however, due to the common C1 term. 
Consider an illustrative case of a class CC1 structure (H/C0 < 1) in 
Table 4b, where a high cost of increasing safety (C1/C0) results in a 
βt,1 = 3.1. Human occupancy is typically low in CC1 structures and the 
Nf is therefore also likely to be low in the event of failure, resulting in a 
high K1 value and thus βt,1 ≈3.1, assuming the γ, ω and GΔ are the same 
for both cases. The MLSC/LQI criteria are therefore likely to provide 
lower bound reliabilities, whereas economic criteria are more likely to 
govern the design of new structures. 

3.3. Life safety in existing structures 

So far, the advances in the application of human safety in traditional 
structural design and risk-informed design for new-build structures have 
been reviewed. The underlying principles for maintaining acceptable 
human safety levels are similarly applicable to already-existing struc­
tures. Important distinctions are made between new and existing 
structures. The cost to increase safety (C1 – retrofit, repair etc.) in 
existing structures is typically higher than for new structures, the 
remaining working life is often less than the initial design period, and 
the condition of the structure and the loads it is exposed to can be more 
accurately defined compared to what was assumed in design [25]. From 
an economic perspective therefore, the target reliability should be lower 
for existing structures; requiring the same levels as for new structures 
would be uneconomical [17,21,75]. Due to this, human safety re­
quirements can often govern the target reliability of existing structures 
instead of economic considerations. A reliability assessment is typically 
carried out on an existing structure when there are concerns surround­
ing its safety, or when a structure is to be repurposed. 
It is usually prudent to first evaluate whether the structure adheres to 
human safety levels in its current state or not. If it does, an upgrade 
strategy based purely on economic optimisation is optional and can be 
carried out if economically viable. If the structure does not adhere 

..._This content has been truncated to stay below 50000 characters_...
# Dataset-Paris-Agreement-negotiation-meetings

The repository includes the datasets for the UNFCCC meeting leading to the 2015 Paris agreement (participants and speeches) and the UNFCCC negotiation groups, used for the paper "Achieving consensus in multilateral international negotiations: The case study of the 2015 Paris Agreement on climate change" by C. Bernardo, L. Wang, F. Vasca, Y. Hong, G. Shi and C. Altafini.

Abstract: The purpose of this paper is to propose a dynamical model describing the achievement of the 2015 Paris Agreement on climate change. This agreement is the outcome of a complex multiparty negotiation process that lasted more than a decade. To represent the overall negotiation process, we use a two time scale dynamical model. The short time scale corresponds to the discussion process occurring at each meeting and is represented as a Friedkin-Johnsen model, a dynamical multiparty model in which the parties show stubbornness, i.e., tend to defend their positions during the discussion. The long time scale behavior is determined by concatenating multiple Friedkin-Johnsen models (one for each meeting). The proposed model, tuned on real data extracted from the Paris Agreement meetings, achieves a consensus value on a time horizon similar to that of the real negotiations. Quite remarkably, the model is also able to identify a series of parties that exerted a key leadership role in the Paris Agreement negotiation process.



UNFCCC_meetings.xlsx

Each worksheet corresponds to one of the UNFCCC bodies considered in the paper:

COP (Conference of the Parties),
AC (Adaptation Committee),
AFB (Adaptation Fund Board),
CTCN (Climate Technology Centre & Network),
CC-E (Compliance Committee - Enforcement Branch),
CC-F (Compliance Committee - Facilitative Branch),
CGE (Consultative Group of Experts),
CDM EB (Executive Board of the Clean Development Mechanism),
JISC (Joint Implementation Supervisory Committee),
LEG (Least Developed Countries Expert Group),
SCF (Standing Committee on Finance),
TEC (Technology Executive Committee).
The first column contains the list of parties, while the others represent the participation of the corresponding party at the meeting which was held at the date reported in the first row. Each entry can be: 0 (no participation), 1 (participation without speech) and z (> 1, participation with z − 1 speeches).


UNFCCC_negotation_groups.xlsx

The first column contains the list of parties, while the others define the affiliation of the corresponding party to the negotiation group reported in the first row. Therefore, each entry can assume two values: 1 (member) and 0 (no member).

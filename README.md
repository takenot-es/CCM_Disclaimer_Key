# CCM Disclaimer Key

### TotalExpert disclaimers in self-served are called with a specific line. This document is for calling those disclaimers.

#### Sample
`{{ organization.disclaimers.XXXXXXX.content }}`<br>

#### 3024_Branch_Disclaimer
`{{ organization.disclaimers.3024_Branch_Disclaimer.content }}`<br>
Equal Housing Opportunity. All loans subject to underwriting approval. Certain restrictions apply. Call for details. NMLS3029 (www.nmlsconsumeraccess.org) CrossCountry Mortgage, Inc. 520 W. Erie St., Suite 400, Chicago, IL 60654. NMLS1806506. Illinois Residential Mortgage Licensee.

#### 3025_Branch_Disclaimer
`{{ organization.disclaimers.3025_Branch_Disclaimer.content }}`<br>
Equal Housing Opportunity.  All loans subject to underwriting approval. Certain restrictions apply. Call for details. NMLS3029 (www.nmlsconsumeraccess.org) CrossCountry Mortgage, Inc. 520 W. Erie St., Suite 400, Chicago, IL 60654. NMLS1806506. Illinois Residential Mortgage Licensee.

#### 4050_Branch_Disclaimer
`{{ organization.disclaimers.4050_Branch_Disclaimer.content }}`<br>
Equal Housing Opportunity.  All loans subject to underwriting approval. Certain restrictions apply. Call for details. NMLS3029 (www.nmlsconsumeraccess.org) CrossCountry Mortgage, Inc. 169 Saxony Road Suite 104, Encinitas, CA. NMLS1820222. Licensed by the Department of Business Oversight under the California Residential Mortgage Lending Act.

#### 5518_Branch_Disclaimer
`{{ organization.disclaimers.5518_Branch_Disclaimer.content }}`<br>
Equal Housing Opportunity.  All loans subject to underwriting approval. Certain restrictions apply. Call for details. NMLS3029 (www.nmlsconsumeraccess.org) CrossCountry Mortgage, Inc. 33434 8th Avenue South Side Suite 107, Federal Way, WA 98003. NMLS1621904.

#### CA
`{{ organization.disclaimers.CA.content }}`<br>
Licensed by the Department of Business Oversight under the California Residential Mortgage Lending Act.

#### Consult_a_Tax_Advisor
`{{ organization.disclaimers.Consult_a_Tax_Advisor.content }}`<br>
Consult a tax advisor for further information. All loans subject to underwriting approval. Certain restrictions apply. Call for details.

#### DBA_BeMortgage
`{{ organization.disclaimers.DBA_BeMortgage.content }}`<br>
N/A


#### Doctor
`{{ organization.disclaimers.Doctor.content }}`<br>
Available to medical doctors, dentists, podiatrists, ophthalmologists and veterinarians with a minimum of a M.D., D.O., D.D.S. or D.M.D. degree. Subject to terms and conditions. Not all borrowers will qualify. Contact Cross Country Mortgage to find out more.

#### FHA
`{{ organization.disclaimers.FHA.content }}`<br>
CrossCountry Mortgage, Inc. is an FHA Approved Lending Institution and is not acting on behalf of or at the direction of HUD/FHA or the Federal government.

#### GA
`{{ organization.disclaimers.GA.content }}`<br>
Georgia Residential Mortgage Licensee.

#### General_Branch_Disclaimer
`{{ organization.disclaimers.General_Branch_Disclaimer.content }}`<br>
Equal Housing Opportunity. All loans subject to underwriting approval. Certain restrictions apply. Call for details. NMLS3029 (www.nmlsconsumeraccess.org) CrossCountry Mortgage, Inc.  

#### HECM
`{{ organization.disclaimers.HECM.content }}`<br>
To obtain a HECM, you must take an approved counseling course available at little to no cost and receive a certificate of completion that will be required during the application process. While you won‚Äôt make any mortgage payments, you will still be responsible for property taxes and homeowners insurance and upkeep of the property.

#### HELOC
`{{ organization.disclaimers.HELOC.content }}`<br>
Failure to pay on your HELOC could damage your credit standing and result in the loss of your home through foreclosure.

#### IL
`{{ organization.disclaimers.IL.content }}`<br>
Illinois Residential Mortgage Licensee.

#### KS
`{{ organization.disclaimers.KS.content }}`<br>
Kansas Licensed Mortgage Company.

#### MA
`{{ organization.disclaimers.MA.content }}`<br>
CrossCountry Mortgage, Inc. is a licensed mortgage lender in the Commonwealth of Massachusetts.

#### MS 
`{{ organization.disclaimers.MS.content }}`<br>
Mississippi Licensed Mortgage Company.

#### NH
`{{ organization.disclaimers.NH.content }}`<br>
Licensed by the New Hampshire Banking Department.

#### NJ
`{{ organization.disclaimers.NJ.content }}`<br>
Licensed by the New Jersey Department of Banking and Insurance.

#### NY
`{{ organization.disclaimers.NY.content }}`<br>
Licensed Mortgage Banker ‚Äì New York State Banking Department.

#### PERL_DBA
`{{ organization.disclaimers.PERL_DBA.content }}`<br>
N/A

#### Realtor
`{{ organization.disclaimers.Realtor.content }}`<br>
This piece is for professional realtor use only. It is not intended for consumer use.

#### REVERSE
`{{ organization.disclaimers.REVERSE.content }}`<br>
To obtain a reverse mortgage, you must take an approved counseling course available at little to no cost and receive a certificate of completion that will be required during the application process. While you won‚Äôt make any mortgage payments, you will still be responsible for property taxes and homeowners insurance.

#### RI
`{{ organization.disclaimers.RI.content }}`<br>
Rhode Island Licensed Lender.

#### Standard_Disclosure
`{{ organization.disclaimers.Standard_Disclosure.content }}`<br>
All loans subject to underwriting approval. Certain restrictions apply. Call for details. NMLS3029 (www.nmlsconsumeraccess.org).

#### Standard_Rate_Disclosure
`{{ organization.disclaimers.Standard_Rate_Disclosure.content }}`<br>
Payment example does not include taxes, insurance or assessments.  Actual payment obligations may be greater and may vary. {% if loan_scenarios[0] %}Principal and Interest payment of ${{ loan_scenarios[0].monthly_payment | formatNumber: 2}} is based upon a ${{ listing.list_price | formatNumber }} purchase price, {{ loan_scenarios[0].down_payment_pct }}% down payment, {{ loan_scenarios[0].product_name }} mortgage and rate of {{ loan_scenarios[0].rate | formatNumber: 3 }}%/{{ loan_scenarios[0].apr | formatNumber: 3 }}% Annual Percentage Rate (APR).{% endif %}{% if loan_scenarios[1] %}Principal and Interest payment of ${{ loan_scenarios[1].monthly_payment | formatNumber: 2}} is based upon a ${{ listing.list_price | formatNumber }} purchase price, {{ loan_scenarios[1].down_payment_pct }}% down payment, {{ loan_scenarios[1].product_name }} mortgage and rate of {{ loan_scenarios[1].rate | formatNumber: 3 }}%/{{ loan_scenarios[1].apr | formatNumber: 3 }}% Annual Percentage Rate (APR).{% endif %}{% if loan_scenarios[2] %}Principal and Interest payment of ${{ loan_scenarios[2].monthly_payment | formatNumber: 2}} is based upon a ${{ listing.list_price | formatNumber }} purchase price, {{ loan_scenarios[2].down_payment_pct }}% down payment, {{ loan_scenarios[2].product_name }} mortgage and rate of {{ loan_scenarios[2].rate | formatNumber: 3 }}%/{{ loan_scenarios[2].apr | formatNumber: 3 }}% Annual Percentage Rate (APR).{% endif %}{% if loan_scenarios[3] %}Principal and Interest payment of ${{ loan_scenarios[3].monthly_payment | formatNumber: 2}} is based upon a ${{ listing.list_price | formatNumber }} purchase price, {{ loan_scenarios[3].down_payment_pct }}% down payment, {{ loan_scenarios[3].product_name }} mortgage and rate of {{ loan_scenarios[3].rate | formatNumber: 3 }}%/{{ loan_scenarios[3].apr | formatNumber: 3 }}% Annual Percentage Rate (APR).{% endif %} Mortgage Insurance Premium (MIP) is required for all FHA loans and Private Mortgage Insurance (PMI) is required for all conventional loans where the LTV is greater than 80%. Rate(s), APR(s) and payment info is valid as of {{ template.timestamp | date: '%D' }} and assumes a first lien position, 740 FICO score, 25 day rate lock, based on a {% if listing.condo %}condo{% elsif listing.multi_family %}multi-family home{% else %}single family home{% endif %} in {{ listing.state }}. All terms are subject to change without notice. Loans are subject to underwriting guidelines and applicant‚Äôs credit profile, not all applicants will be approved. Contact CrossCountry Mortgage for more information.

#### Subject_to_terms_and_conditions
`{{ organization.disclaimers.Subject_to_terms_and_conditions.content }}`<br>
Subject to terms and conditions.

#### TX
`{{ organization.disclaimers.TX.content }}`<br>
This office is licensed and examined by the Office of the Consumer Credit Commissioner of the State of Texas.

#### USDA
`{{ organization.disclaimers.USDA.content }}`<br>
Subject property and borrower income and credit must qualify to USDA guidelines.

#### VA
`{{ organization.disclaimers.VA.content }}`<br>
Licensed by the Virginia State Corporation Commission.

#### VA_Loans
`{{ organization.disclaimers.VA_Loans.content }}`<br>
Certificate of Eligibility required for VA loans.


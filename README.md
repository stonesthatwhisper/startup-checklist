# Startup Incorporation Checklist
#### How to bootstrap a Delaware C-corp (or S-corp) with employee(s) in California

**Disclaimer:** I am not a lawyer (IANAL). This list is intended as a learning tool and you should *definitely* consult with a lawyer if you have any questions or concerns. This is a work in progress, so suggestions and pull requests are welcome! 

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

##### Intro
Other than building a product people want, incorporating a new business is essential to raising money, opening a bank account, and creating a legal entity for contracts and other liabilities. For technical folks like me, it's the "necessary evil" of founding a company and just needs to get done. Having gone through this recently, I made a checklist in case I'd have to do it again in the near future. Why you should incorporate in DE is outside the scope of this article, but [other folks have written good answers](https://www.quora.com/Why-do-most-technology-startups-incorporate-in-Delaware).

Some notes:
- The full process will take several weeks to complete
- Most steps are sequential and depend on an earlier step being complete
- Many steps require the use of snail mail or a [fax machine](#tools)
- For brevity, Delaware and California are shortened to *DE* and *CA*
- Again, consult your lawyer. Some will defer fees for startups

# The checklist
#### Register with DE
- [ ] Choose a name for your business and check that it's available. [DE Name Search](https://icis.corp.delaware.gov/Ecorp/EntitySearch/NameSearch.aspx) & [CA Name Search](https://businesssearch.sos.ca.gov)
- [ ] Generate incorporation documents and sign them [[free document service]](#free-tool1)
- [ ] Buy registered agent service in DE - **1 yr Free**
- [ ] File incorporation docs with DE - **~$150 including fees for 1 week service**
  - You can do this yourself, but it will probably take longer and not save you much money
  - Make sure the County is included in the address of the registered agent on the Certificate of Incorporation

#### First steps with the IRS
- [ ] Apply for a Federal Employer Identification Number (EIN) - **Free**
  - [IRS info & form](https://www.irs.gov/businesses/small-businesses-self-employed/apply-for-an-employer-identification-number-ein-online)
  - Expect the IRS to mail you a document containing your *EFTPS Pin*. This allows you to pay federal taxes electronically
- [ ] *(for founders with stock vesting)* File 83b election within 30 days of stock grant
  - reference: https://www.irs.gov/irb/2012-28_IRB/ar12.html
  - example letter: http://accountalent.com/83b-elections-for-dummies/
  - include 2 extra signed copies and self-addressed stamped return envelope
- [ ] *(only for S-corp)* File IRS Form 2553 to convert C-corp to S-corp
  - [IRS Form 2553](https://www.irs.gov/pub/irs-pdf/f2553.pdf)

**NOTE:** Most of the following steps require a valid U.S. checking account and the steps above allow you to open an account. This is probably the best time to do so.

#### Register with CA
**NOTE:** This section applies to companies that are doing business or have employees in CA - similar requirements apply for other states.

- [ ] *(optional, see below)* Order certified copy of *Certificate of Good Standing* from DE - **$50**
  - Within 6 months of DE registration, you can use the "Filed Certificate of Incorporation" signed and stamped by Secretary of DE (document forwarded by DE registered agent following incorporation)
  - Fill out [DE fillable form](https://corp.delaware.gov/updatedcertmemoandinstructionsOct717.pdf) and fax to (302) 739-3812. [more info](https://corp.delaware.gov/directweb.shtml)
  - Or, find [an agent with online access](https://corp.delaware.gov/remoteagts.shtml)
- [ ] Sign up for Registered agent service in CA **1 yr free**
- [ ] Register your *foreign entity* with CA Secretary of State - **$100**
  - Fill out [CA form S&DC - S/N](http://bpd.cdn.sos.ca.gov/corp/pdf/foreign/s&dc-sn.pdf)
  - Make sure **NOT** to include mailing address for registered agent
  - Include either *Filed Certificate of Incorporation* (signed and stamped by Secretary of DE) or, if registering in CA 6mo+ after incoporation, *DE Certificate of Good Standing* with mailed form
- [ ] *(optional for solo founders)* Exclude yourself from paying SDI taxes 
  - [CA form DE459](http://www.edd.ca.gov/pdf_pub_ctr/de459.pdf)
- [ ] Within 90 days of CA registration, file Statement of Information (SI-550) - **$25**
    - eFile [CA Form SI-550](http://bpd.cdn.sos.ca.gov/corp/pdf/so/corp_so550.pdf) via [CA Secretary of State website](https://businessfilings.sos.ca.gov/)
    - *if multiple directors*, also attach [CA Form SI-550A](http://bpd.cdn.sos.ca.gov/corp/pdf/so/si-550a.pdf) if sending by mail


  
#### Set up payroll tax payments with IRS and CA
- [ ] Sign up to make IRS payroll tax payments electronically - **Free**
  - Enroll via phone call to IRS 1-800-555-3453 
    - have your EFTPS Pin and checking account info handy
    - be prepared to write down *enrollment number*
  - Set password via [EFTPS password form](https://www.eftps.gov/eftps/login/forgotPassword)
  - Confirm enrollment via [EFTPS login form](https://www.eftps.gov/eftps/login/loginInitial)
- [ ] Register with CA Employer Development Department (CA EDD) - **Free**
  - [CA EDD Enrollment](http://www.edd.ca.gov/Payroll_Taxes/e-Services_for_Business.htm)
- [ ] Sign up with Social Security Business Services - **Free**
  - guide: https://support.waveapps.com/entries/60125574-Social-Security-Business-Services-Online-Registration-Guide
  - form: https://www.ssa.gov/bso/bsowelcome.htm


## Recurring items

- [ ] *varies* File and pay CA payroll taxes
  - *quarterly* eFile [CA Form DE9](http://www.edd.ca.gov/pdf_pub_ctr/de9.pdf) & [CA Form DE9C](http://www.edd.ca.gov/pdf_pub_ctr/de9c.pdf)
  - File forms via [CA EDD website](https://eddservices.edd.ca.gov/tap/secure/eservices)
- [ ] *varies* File and pay Federal payroll taxes
  - Mail or eFile federal tax form (Medicare, Social Security, Federal Income Tax) [(reference)](https://www.irs.gov/taxtopics/tc757.html) [(eFile tool)](#tool3)
    - *quarterly* use [IRS Form 941](https://www.irs.gov/pub/irs-pdf/f941.pdf) [(instructions)](https://www.irs.gov/pub/irs-pdf/i941.pdf)
    - *yearly* use [IRS Form 944](https://www.irs.gov/pub/irs-pdf/f944.pdf) [(instructions)](https://www.irs.gov/pub/irs-pdf/i944.pdf)
  - Pay via [EFTPS website](https://www.eftps.gov/eftps/index.jsp)
- [ ] *yearly* File federal tax return
  - *(S-corp only)* File [IRS Form 1120S](https://www.irs.gov/pub/irs-pdf/f1120s.pdf) ([instructions](https://www.irs.gov/pub/irs-pdf/i1120s.pdf))
  - *(C-corp only)* File [IRS Form 1120](https://www.irs.gov/pub/irs-pdf/f1120.pdf) ([instructions](https://www.irs.gov/pub/irs-pdf/i1120.pdf))
  - *(LLC-only)* depends on ownership structure, but partnerships must distribute [IRS Schedule K-1](https://www.irs.gov/pub/irs-pdf/f1065sk1.pdf) to each owner
- [ ] *yearly* File DE annual report and pay franchise tax **>= $350**
  -  https://corp.delaware.gov/paytaxes.shtml
- [ ] *yearly* File CA statement of information **$25**
  - File [CA Form SI-550](http://bpd.cdn.sos.ca.gov/corp/pdf/so/corp_so550.pdf) via [CA Secretary of State website](https://businessfilings.sos.ca.gov/)
- [ ] *yearly* File CA tax return **>= $800**
  - *Note:* First year loss might waive $800 minimum [[ref]](http://www.taxes.ca.gov/corps.shtml)
  - File and pay via [CA Franchise Tax Board (FTB)](https://www.ftb.ca.gov/online/webpay/Business_Entities.asp)
- [ ] *yearly* Send W2 to employees [(eFile tool)](#tool3)
- [ ] *yearly* File W3 with IRS
- [ ] *yearly* Send 1099 to contractors, lawyers, et. al. [(eFile tool)](#tool3)

## <a name=tools></a>Tools & References
### Free or mostly-free tools
1. <a name=free-tool1></a>[Founder's Workbench](http://www.foundersworkbench.com/document-driver/) - generate incorporation documents
2. <a name=free-tool2></a>[FreeRegisteredAgent](http://www.freeregisteredagent.com/delaware/registered-agent-service/) - one year of free registered agent service in DE and/or CA
3. <a name=free-tool3></a>[HelloFax](https://www.hellofax.com?ref=43d04ff4&s=F) - send faxes without a fax machine
4. <a name=free-tool4></a>[Wave](https://www.waveapps.com/) - free accounting software, with extra services for a $fee

### <a name=nonfree-tools></a>Non-free tools
1. <a name=tool2></a>[Clerky](https://www.clerky.com/offerings#company-formation) - software to handle the complete set of company formation paperwork online (incorporation, appointing directors and officers, issuing stock, protecting IP, etc.)
2. <a name=tool4></a>[Stripe Atlas](https://stripe.com/atlas) - like Clerky, handles most of the company formation paperwork, it will also automatically setup a bank account with SVB as well as a Stripe account
3. <a name=tool1></a>[InCorp](http://www.freeregisteredagent.com/delaware/registered-agent-service/) - will file DE incorporation papers quickly on your behalf for ~$150, including state fees
4. <a name=tool3></a>[Tax1099](https://www.tax1099.com) - e-file federal tax forms (e.g. tax return, 1099, W2, etc), small fee per form
5. <a name=tool5></a>[Intuit 1099 service](https://iop.intuit.com/welcome/1099.jsp) - generate and e-file 1099 forms, small fee per form 
6. <a name=tool6></a>[VirtualPostMail](https://www.virtualpostmail.com/) - virtual mailbox for real mail. Good for nomadic workers and short-term offices. Also offers free registered agent in CA with paid plan

### References
* **Q:** Choosing between C-corp, S-corp, and LLC? [Answer](http://www.obliviousinvestor.com/llc-vs-s-corp-vs-c-corp/)
* **Q:** Why incorporate in DE? [Answer](https://www.quora.com/Why-do-most-technology-startups-incorporate-in-Delaware)

## Known unknowns
- Sales taxes
- Generate *Terms of Service*, *Privacy Policy*, etc ([Docracy.com](http://www.docracy.com/) has some good templates)
- Liability insurance
- Start using bookkeeping software right away to track expenses, income, etc. Lots of free/affordable options


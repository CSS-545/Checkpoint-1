# Project Summary: Greenie

` Swanand Wagh and Azmeen Kausar`

## Overview

Greenie's mission is to instill trust in the hiring process by verifying both candidates and companies. Our platform creates value for companies by allowing HR teams to access verification reports instantly, eliminating weeks of waiting. Simultaneously, we empower candidates by giving them total control over their personal data, democratizing verifications for all.

## Value Proposition

- Greenie addresses inefficiencies in the professional verification landscape that impact both individual employees and companies.
- For employees, the lack of a centralized repository for important documents, inaccessible verification reports, and the recurring need to undergo verification with each job change, compounded by persistent follow-ups from HR departments or Background Verification Companies (BVCs), pose significant challenges.
- For companies, the existing verification processes are not only costly, averaging between $800 to $1100 per employee, but also slow, with turnaround times (TAT) extending from 14 to 30 days. Additionally, the prevalence of false positive results on hiring platforms further complicates the hiring process.
- Our Greenie’s innovative platform proposes to streamline these processes, significantly reduce costs, and TAT, and improve the overall accuracy and accessibility of professional verifications, thus offering a robust solution to these persistent industry pain points.

## Primary Purpose

The project aims to democratize professional verification processes, ensuring that both candidates and companies can trust the speed and reliability of the background checks provided. This contributes to a more streamlined hiring and verification process.

## Target Audience

Greenie primarily targets HR professionals and recruiters across various industries, in addition to job seekers and employees who need to maintain a verified professional profile. The platform aims to integrate seamlessly with major HRMS platforms and offers a user-friendly and secure interface to attract users.

## Success Criteria

The success of Greenie will be evaluated based on several metrics, including user adoption rates, reduction in average cost and time for verifications, customer satisfaction scores, and the platform’s ability to secure partnerships with major HR and recruitment platforms.

## Competitor Analysis

Unlike traditional verification services like FirstAdvantage, IDIFY, Digilocker and SpringRole, which often involve lengthy, manual and costly processes, Greenie offers a faster, more affordable, and secure solution that positions it favorably against competitors.

## Monetization Model

Greenie plans to generate revenue through subscription models for HR professionals and premium accounts for candidates. The platform also explores potential B2B partnerships for bulk verification services, diversifying its revenue streams. Greenie OAuth API will be available for third-party integrations.

## Initial Design (MVP)

#### Scope:

- **User Authentication**: Implement user authentication mechanism.
- **Location Verification**: Implement location verification for candidates.
- **Work Verification**: Implement work verification for candidates. (If time permits)
- **ID Verification**: Implement ID verification for candidates. (If time permits)

### Known Limitations:

- **Limited Document Types**: Initially support only PDFS.
- **Basic UI/UX**: The UI/UX may lack polish and advanced features initially.
- **Manual Verification**: Verification processes may rely on manual intervention initially (Peer-Peer verification).
- **Limited Integration**: Initial integration with third-party services and APIs may be limited.

## UI/UX Design

### Important Components:

- **Home Screen**: A screen with information about the platform and its features.
- **User Dashboard**: A dashboard for users to manage verification requests, messages, and profile information.
- **Document Upload**: User-friendly interface for candidates to upload verification documents.
- **Verification Status**: Clear indicators to show the status of verification requests.

## Technical Architecture

### Necessary Components:

- **Frontend Framework**: React Native for building the UI.
- **Backend Framework**: Node.js or Firebase for handling server-side logic.
- **Database**: MongoDB or Firebase Firestore for storing user data.
- **Cloud Storage**: Azure Blob Storage or Firebase Storage for storing verification documents.
- **Authentication Service**: Implement OAuth or JWT for user authentication and authorization.
- **Third-Party APIs**: Integration with third-party APIs like Firebase API, ZOOP API, etc.

## Technical Challenges and Solutions

### Performance Issues

- **Challenge:** High traffic volumes could lead to slow response times and degraded performance.
- **Solution:** Implement caching mechanisms to reduce database load. Utilize content delivery networks (CDNs) for static assets. Optimize database queries and code execution for efficiency. Implement load balancing to distribute traffic evenly across servers.

### Verification & Security Issues

- **Challenge:** Ensuring the security and integrity of sensitive candidate data during verification processes.
- **Solution:** Utilize encryption techniques to secure data transmission and storage. Implement multi-factor authentication for user accounts. Regularly audit and update security protocols to mitigate vulnerabilities. Conduct penetration testing to identify and address potential security weaknesses.

### Scaling Issues

- **Challenge:** Accommodating rapid growth and increased demand without sacrificing performance.
- **Solution:** Design the platform architecture for horizontal scalability, allowing for easy expansion of resources. Utilize cloud-based infrastructure to dynamically adjust resources based on demand. Implement auto-scaling mechanisms to automatically provision additional resources during peak usage periods. Regularly monitor system performance and scalability metrics to proactively address any bottlenecks.

## Questions for Feedback:

1. **User Experience**: How can we further enhance the user experience to make the verification process more intuitive and streamlined?
2. **Data Privacy**: Are there any additional measures we can implement to ensure compliance with evolving data privacy regulations?
3. **Market Expansion**: What strategies can we employ to effectively expand into new geographic regions and industries?
4. **Feature Prioritization**: Which features do users consider most essential, and which ones can be deprioritized or improved?
5. **Integration Capabilities**: Are there specific HRMS platforms or third-party services that users would like to see integrated with Greenie for enhanced functionality?

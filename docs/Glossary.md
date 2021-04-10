# Glossary 

## Foundational Glossaries

The Canadian Credential Network is working on a convergence of industry terms between several glossary efforts, namely:

* [PCTF Glossary Recommendation](https://diacc.ca/wp-content/uploads/2020/09/PCTF-Glossary-Final-Recommendation_V1.0.pdf)
* [Sovrin Glossary](https://docs.google.com/document/d/1gfIz5TT0cNp2kxGMLFXr19x1uoZsruUe_0glHst2fZ8)
* [TOIP Glossary](*to be added*)

The contents herein are considered additional terms specific to the **Canadian Credential Network**.

## Canacred Glossary terms and definitions

Currently we are in the process of adding new terms and definitions. Below are the terms that need clarification and defining. Some of them will be removed from Canacred Glossary. 

**Self-Certification** - the process of an Entity issuing a credential that is presented to other participants of the digital ecosystem when the credential itself is issued by that same Entity. 

**Claim** - A statement about a Subject or a statement about an association that exists between two or more Subjects. A claim is expressed by means of one or more attributes.

**Accreditation** - the process performed by designated Trust Actor of verifying that Canacred Participant conforms to the requirements of the Governance Framework. Accreditation is performed to add reasonable assurance that the Participant is meeting established trust criteria.

**Trust Registry** - the Trust Role that mediate the creation and veriofication of identifiers, keys, and other relevant data, such as verifiable credential schemas, revocation registries, issuer public keys, and so on, which might be required to use verifiable credentials. 

**Governance Framework** - A set of agreed on principles, definitions, standards, specifications, conformance criteria, contracts, and assessment approach by which Canacred Participants agree to be governed in order to achieve desired Levels of Assurance. Canacred Governance Framework will consist of Master Document, Glossary, Legal Agreements, Core Business Policiess and Trust Assurance Framework.

**Trust Assurance Framework** - A set of human readable and cryptographic documents containing policies, definitions describing Trust Actors and Trust Roles, as well as Trust Elements, Trust Evidence and Conformance Criteria. These documents define Subjects of the Trust Assurance Framework as well as their processes.

**Canacred Participant** - An Entity that has at least one DID in the Canacred Network. There will be two types of Participants in the Canacred Network: Contributors and Readers. Contributor is the Participant with write and read access to the Canacred Network. Reader is the Participant with read access only to the Canacred Network.

**Trust Actor** - Entity that create, assess, and opinion on legal, governance and business frameworks where Canacred operates. Examples: Federal, provincial governments and government entities.

**Trust Role** - Accreditated Contributors of the Canacred that have the right to make trust assertions about other Participants. Examples: Steward, Issuer, Registrar.

## Abstract from  PCTF Glossary**:

The PCTF Glossary provides definitions and examples for terms that appear across DIACC PCTF documentation. The content of the PCTF Glossary is:
1. **Terms**–The words or phrases that appear frequently and that are used with a specific intent (i.e., not their everyday English meaning) in the PCTF documentation
2. **Definitions**–A statement that provides the accepted and precise meaning of the associated term in the PCTF context
3. **Examples**–Examples or non-examples may be included to help clarify the intended meaning of a term; the examples provided are not intended to be an exhaustive list.
4. **Synonyms**–Terms with same or similar meaning used in other communities of interest

## Terms from PCTF Glossary

### Entity
An entity is a thing with a distinct and independent existence such as a person, organization, or device that can be subject to legislation, policy, or regulations within a context, and which may have certain rights, duties, and obligations. An entity can perform one or more roles in the digital ecosystem. 
There are two types of entities: atomic entities and compound entities. An atomic entity is an entity that cannot be decomposed into smaller units. Persons are atomic entities. A compound entity is an entity that is comprised of one or more atomic entities. Organizations are compound entities.

### Relationship
A relationship is an association between two or more entities. The entities in the relationship can be any combination of atomic entities and compound entities. Relationships between entities must be differentiated from interactions between entities (i.e.,
transaction execution).

### Steward
A general term for an organization that is responsible for providing and maintaining a portion of the infrastructure necessary to establish a public identity utility. Minimally, the organization must meet the requirements to be a member of the public identity utility and must operate at least one ```Node```.

### Node
A computer network server running an instance of the code necessary to operate a distributed ledger or blockchain. In the Canadian Credential Network, a Node is operated by a Steward running an instance of the Canacred Open Source Code to maintain the Canacred Network Utility ( or DID Ledger). A Node must be either a Validator Node or an Observer Node.

### Canacred Open Source Code
The computer software that is installed on all Nodes associated with the Canacred Network Utility (CCNU). This code determined by the Canacred Board of Directors. The CCNU adheres to code selection and version guidance provided by the Technical Steering Committee ("TSC") of the Canacred Wallet Project. The TSC collaborates within the Hyperledger Indy Project of the Linux Foundation to establish a TSC approved version of Hyperledger Indy within the the Canacred Code Repository managed by the TSC.

### Canacred Ledger Environments
The corpus of DID Ledgers used by the Canadian Credential Network to operate the Canacred Network Utility. For example: ```prod```, ```test```, and ```dev```.

### Governing Body

An organization or consortium that is responsible for the management of an Identity Utility Network.

### DID Ledger
A distinct system of domain specific ledgers operated by decentralized peer nodes and associated with a DID Namespace.
See *Identity Utility Network (IUN)*

### Identity Utility Network (IUN)

A distinct system of domain specific ledgers operated by decentralized peer nodes and associated with a DID Namespace.
Preferably built on Hyperledger Indy, this ```DID Ledger```, is governed by an independent governing body and its own governance framework. Due to the overuse of terms such as "Network" and "Ledger", the term "Utility" has been accepted by the Canadian Credential Network to allow for additional clarity.

### Decentralized DID Namespace Registry (DDNR)

Provides registration, discovery, and access for an Identity Utility Network.

### Identity Utility Administrator

See *Utility Service Provider*

### Utility Service Provider

The provider of operational and maintenance services for an Identity Utility Network.

### Key Recovery
The process of recovering access to and control of a set of Private Keys—or an entire Wallet—after loss or compromise. Key Recovery is a major focus of the emerging DKMS standard for cryptographic key management. See also Recovery Key.

### Recovery Key
A special Private Key used for purposes of recovering a Wallet after loss or compromise. In the DKMS key management protocol, a Recovery Key may be cryptographically sharded for secret sharing among multiple Trustees.

### Participation Management System
The means by which the Governing Board tracks participation entitlements and status. There will be two types of **Participants**: **Contributors** - those with the write access and **Readers*** - those with the read access only.


### Digital Trust Ecosystem
An interdependent group of enterprises, people and/or things that share a standardized trust model for mutually beneficial purposes, such as consumer and commercial interactions that are verifiable.

### CLI Private Key
The Private-Key used by a Steward when interacting with the Indy CLI.

### Validator Private Key
The Private-Key used by the Validator Node when performing concensus.

Participation Application Practices and Procedures, 

Hosting Provider,

Validator and Observer Nodes, 

*Crisis Management Plan*, 

Network Interface Controller, 

Diffuse Trust Principle, 

High Availability Principle, 

Transaction Author, 

Data Controller, 

Data Processor, 

FIFO Waiting [list](https://queue-it.com/queue-first-in-first-out/)

Trust Anchor

**?** Trust Mechanism

**?** Trust Author
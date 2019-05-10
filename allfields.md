## LeadIQ Contact Search - All Fields

```
query SearchPeople($input: SearchPeopleInput!) {
  searchPeople(input: $input) {
    totalResults
    hasMore
    results {
      _id
      name {
        first
        middle
        last
      }
      personalEmails {
        type
        status
        sources {
          source
          status
          providerIds
        }
        value
        updatedAt
      }
      personalPhones {
        type
        status
        sources {
          source
          status
          providerIds
        }
        value
        updatedAt
      }
      linkedin {
        linkedinUrl
        linkedinId
        sources {
          source
          status
          providerIds
        }
      }
      currentPositions {
        companyId
        title
        dateRange {
          start
          end
        }
        sources {
          source
          status
          providerIds
        }
        companyInfo {          
          name
          address
          alternativeNames
          type
          country
          domain
          emailDomains
          industry
          logoUrl
          locationInfo {
            formattedAddress
            street1
            street2
            city
            areaLevel1
            country
            postalCode
          }
          phones
          numberOfEmployees
          source          
        }
        emails {
          type
          status
          sources {
            source
            status
            providerIds
          }
          value
          updatedAt
        }
        phones {
          type
          status
          sources {
            source
            status
            providerIds
          }
          value
          updatedAt
        }
        updatedAt
      }
      pastPositions {
        companyId
        title
        dateRange {
          start
          end
        }
        sources {
          source
          status
          providerIds
        }
        companyInfo {          
          name
          address
          alternativeNames
          type
          country
          domain
          emailDomains
          industry
          logoUrl
          locationInfo {
            formattedAddress
            street1
            street2
            city
            areaLevel1
            country
            postalCode
          }
          phones
          numberOfEmployees
          source          
        }
        emails {
          type
          status
          sources {
            source
            status
            providerIds
          }
          value
          updatedAt
        }
        phones {
          type
          status
          sources {
            source
            status
            providerIds
          }
          value
          updatedAt
        }
        updatedAt
      }
    }
  }
}
```

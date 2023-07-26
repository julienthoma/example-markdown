# Dashboard

## Analytics Figures

### Bond Rating Allocation

The **Bond Rating Allocation** displays the marketvalue per bond rating of all bonds in the currently selected portfolio.

#### Data

The data used for the calculation is the **marketvalue** of all bonds.
The rating allocation is based on the worst rating of the bond. If a bond is unrated, the worst issuer rating is used.

#### Calculation of the allocation

All marketvalues of the relevant bond positions are summed up per rating.

### Bond Term Structure Allocation

The **Bond Term Structure Allocation** displays the marketvalue regarding the term structure of all bonds in the currently selected portfolio.

#### Data

The data used for the calculation is the **marketvalue** of all bonds.
The allocation is based on the maturity of the bonds.
The term structure is subdivided as follows: 0-1 year, 1-3 years, 3-5 years, 5-10 years, >10 years.
For callable bonds the next call date is used instead of the maturity.

#### Calculation of the allocation

All marketvalues of the relevant bond positions are summed up regarding the term structure.

### Country Allocation

The **Portfolio Country Allocation** displays the marketvalue per country of all assets in the currently selected portfolio.

#### Data

The data used for the calculation is the **marketvalue** of all assets. 
The allocation is based on the country of domicile of the issuer for all assets with an issuer (incl. OTC derivatives). 
For funds the geographic focus is used.

#### Calculation of the allocation

All marketvalues of the relevant positions are summed up per country.

### Sector and Country Allocation

The **Portfolio Sector and Country Allocation** displays the exposure per GICS sector and country of domicile of all assets in the currently selected portfolio which have a corporate issuer.

#### Data

The data used for the calculation is the **Total Exposure** of all assets related to the NAV. 
The allocation is based on the GICS sector and the country of domicile of the corporate issuer. 
Only assets are considered which have a corporate issuer with a GICS sector and a country of domicile.

#### Calculation of the Allocation

The sum of all Asset Exposures per Sector and Country is the **Total Exposure** of all relevant positions summed up per sector and country of domicile.


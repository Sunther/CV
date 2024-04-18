
```mermaid
    %%{init:
        { 'logLevel': 'debug', 'theme': 'neutral' ,
            'themeVariables': {
                'git0': '#948a54',
                'git1': '#17375e',
                'git2': '#12da08',
                'git3': '#8eb4e3',
                'git4': '#558ed5',
                'git5': '#dcf01c',
                'git6': '#ffffff',
                'git7': '#ffffff',
                'commitLabelColor': '#000000',
                'commitLabelBackground': '#ffffff',
                'commitLabelFontSize': '20px',
                'tagLabelFontSize': '13px'
            },
            'gitGraph': {
                'rotateCommitLabel': false,
                'showBranches': true,
                'mainBranchName': 'Life',
                'mainBranchOrder': 1,
                'parallelCommits': false,
                'showCommitLabel': true
            }
        }
}%%

gitGraph TB:
    commit id: "S"

    checkout Life
    branch GCE order: 2
    commit id: "Science Branch"
    checkout Life
    merge GCE id: "2012"
    
    branch UPC order: 3
    commit id: "Degree"
    checkout Life
    commit id: "2015"
    branch TSI order: 4
    commit id: "Intern"
    checkout UPC
    merge TSI
    checkout Life
    merge UPC id: "2017"

    branch Courses order: 0
    checkout Life
    branch Vueling order: 5
    checkout Courses
    commit id: "Angular: Getting Started (6h)"
    checkout Courses
    commit id: "Automation with PowerShell Scripts (3h)"
    checkout Vueling
    commit id: "Application Management"
    checkout Courses
    commit id: "Big Data I (30h)"
    checkout Vueling
    commit id: "Vueling University (200h)"
    checkout Courses
    commit id: "Blockchain in the industry 4.0 (8h)"
    checkout Vueling
    commit id: "IT Operations Developer"
    checkout Courses
    commit id: "Cyber-intelligence and cybersecurity (20h)"
    checkout Life
    merge Vueling id: "2022"

    checkout Courses
    commit id: "Getting started with Docker workshop (3h)"

    checkout Life
    branch Mango order: 6
    checkout Mango
    commit id: "Retail Developer"

    checkout Courses
    commit id: "IA"

    checkout Life
    commit id: " "
```

### ***Today - 08/2022 || Retail Developer***
#### ___Mango (Scalian)___
- Develop Windows Services solutions in .NET
- Automate manual repetitive tasks
- Fiscal printer integrations as well as TEF Ingenico new payment system
_______

### ***08/2022 - 04/2019 || IT Operations Developer***
#### ___Vueling Airlines (Aktios)___
- Develop API solutions in .NET Framework
- Automate manual processes with Azure
DevOps’ pipelines and custom applications
_______

### ***04/2019 - 09/2017 || Application Management***
#### ___Vueling Airlines (Aktios)___
- Application management applied to
different technologies as Siebel or .NET
Framework
- Data extractions on T-SQL
- PowerShell scripting
- Client support and project requirements
- Vueling University (200h)
_______

### ***2017 || Degree in Informatics Engineering***
#### ___EPSEVG Universitat Politècnica de Catalunya___
_______

### ***09/2017 - 01/2015 || Intern Developer***
#### ___Telemàtic Solucions Informàtiques S.L.___
- Develop Window Services solutions in .NET
Framework to avoid repetitive tasks
extracting data from database like A3Erp or
Sage
- Multiple meetings with the client to define
functionalities
_______

### ***2012 || GCE - science branch***
#### ___IES Manuel de Cabanyes___
_______

### ***Courses***
<ul>
<li>IA (In-Progress)</li>
<li>Getting started with Docker workshop (3h)</li>
<li>Cyber-intelligence and cybersecurity (20h)</li>
<li>Blockchain in the industry 4.0 (8h)</li>
<li>Big Data I (30h)</li>
<li>Automation with PowerShell Scripts (3h)</li>
<li>Angular: Getting Started (6h)</li>
</ul>

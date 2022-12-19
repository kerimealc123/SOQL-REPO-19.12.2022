# SOQL-REPO-19.12.2022
List<Contact> conList=[SELECT Name, LastName, Id FROM Contact];

for (Integer x=0;x<conList.size();x++){
    System.debug(conList.get(x).Name.toUpperCase());
}
for(contact b:ConList){
    System.debug(b);
}

      for(Contact a:Conlist) {
        System.debug(a.Name.toLowerCase());
    }

List<Case> caseList=[SELECT Origin, Subject, Id, IsDeleted FROM Case];
for(Integer y=0;y<caseList.size();y++){
    System.debug(caseList.get(y));

    for(Case c:CaseList){
        System.debug(c.Id);
    }    
}

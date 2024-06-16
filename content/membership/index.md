---
title: "Mitglied werden"
date: 2024-01-13T10:00:00+01:00
showDate : false
showDateUpdated : false
showHeadingAnchors : false
showPagination : false
showReadingTime : false
showTableOfContents : false
showTaxonomies : false 
showWordCount : false
showSummary : false
---

Die Mitgliedschaft im Förderverein ist der direkteste Weg um uns zu unterstützen.
Um Mitglied zu werden, füllt einfach das folgende Formular aus: 

{{< rawhtml >}}
<style>
input[type=text], input[type=email], input[type=number] {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
}

input[type=submit] {
  width: 100%;
  background-color: #4CAF50;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}

.mitgliedsantrag {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
}
</style>
<div class="mitgliedsantrag">
<form action="https://submit-form.com/CVtYg5Jj1">
    <!-- We don't want users to end up an a different page, see https://documentation.formspark.io/customization/redirection.html#specifying-a-custom-redirect-url -->
    <input
        type="hidden"
        name="_redirect"
        value="https://fv-pfeffermaeuse.de/membership-success/"
    /> 
    <input type="hidden" name="_append" value="false" />
    <!-- Actual form -->
    <label for="name">Name*</label>
        <input type="text" id="name" name="Name" placeholder="Name" required/>
    <br><label for="kind">Kind + Gruppe</label>
        <input type="text" id="kind" name="Kind" placeholder="Kind + Gruppe" />
    <br><label for="street">Straße, Nr.*</label>
        <input type="text" id="street" name="Straße" placeholder="Straße, Nr." required />  
    <br><label for="zip">Postleitzahl, Ort*</label>
        <input type="text" id="zip" name="PLZ" placeholder="PLZ, Ort" required /> 
    <br><label for="phone">Telefonnummer</label>
        <input type="text" id="phone" name="Telefonnummer" placeholder="Telefon" />  
    <br><label for="email">Email*</label>
        <input type="email" id="email" name="Email" placeholder="Email" required />
    <br><label for="beitrag">Jährlicher Mitgliedsbeitrag* <i>(frei wählbar, mindestens 12€)</i></label>
        <input type="number" id="beitrag" name="Beitrag" min="12" value="20">   
    <br><input type="submit" value="Abschicken" />
</form>
</div>
{{< /rawhtml >}}

Alternativ könnt ihr den *[Mitgliedsantrag](20220405_Mitgliedsantrag.pdf)* herunterladen, ausfüllen und an *[Mitgliederverwaltung.FVpfeffermaeuse@outlook.de](mailto:Mitgliederverwaltung.FVpfeffermaeuse@outlook.de)* schicken.

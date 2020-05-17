## ✍️ Description

<!-- Please provide a clear and concise description that includes the type of vulnerability and the impacted package. -->

## 🕵️‍♂️ Proof of Concept

<!-- Please provide a code sample or use case that demonstrates the vulnerability and the outcome of this vulnerability. You can provide a code example or screenshot. For example:
```js
// poc.js
var package = require('vulnerable-package')
var query = {
	pArgs:['test','; touch HACKED; #']
};
package.lookup(query, function(){ console.log('Done!') })
```

or provide a screenshot! -->

## 💥 Impact

<!-- What security impact could the attacker achieve by exploiting this vulnerability? -->

## ☎️ Contact

<!-- Have you made any contact to the package author/maintainer(s) or to another disclosure program? -->

## ✅ Checklist

<!-- Please put an `x` in each box to confirm you have completed the checklist. -->

**In my pull request, I have:**

- [ ] _Created and populated the `README.md` and `vulnerability.json` files_
- [ ] _Provided the repository URL and any applicable [permalinks]([https://help.github.com/en/github/managing-files-in-a-repository/getting-permanent-links-to-files](https://help.github.com/en/github/managing-files-in-a-repository/getting-permanent-links-to-files))_
- [ ] _Defined all the applicable weaknesses ([CWEs]([https://cwe.mitre.org/](https://cwe.mitre.org/)))_
- [ ] _Proposed the CVSS vector items i.e. User Interaction, Attack Complexity_
- [ ] _Checked that the vulnerability affects the latest version of the package released_
- [ ] _Checked that a fix does not currently exist that remediates this vulnerability_
- [ ] _Complied with all applicable laws_
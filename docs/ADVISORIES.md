# Security Advisory Reporting

## Purpose

This document is designed to provide information on how to report security vulnerabilities that have been detected.

## A Quick Note

Advisory reporting is confidential and can only be viewed by repository maintainers or administrators. The repository administrators or maintainers will open a public Github issue in this repository if it has been approved by a maintainer, administrator, etc. No information is shared with 3rd parties or the public unless it is included in a public Github issue. You can request that certain information not be shared in the advisory description in a section seperate from the advsiory description but still included in the advisory details text field (seperate section not provided, you will have to write it in yourself).

## Accessing the Vulnerability System

1. When on the main repository page, select the `Security` tab
2. Read through the security rules if you feel you need more information on the subject
3. Select `Report a Vulnerability`
4. Fill out the provided fields (fill the fields with the information provided below)

## Filling in the Advisory Details Page

This section will explain how to incorporate your data into the `Advisory Details` page.

### Title

In this field, briefly explain what is happening

### Common Vulnerabilities and Exposures (CVE) Identifier

Select `Not Applicable` in the dropdown unless you have an applicable CVE ID. If you have a CVE ID, select `I have an existing CVE ID`. If you have a CVE ID, write it into the field to the right of the dropdown labeled `Existing CVE`.

### Description

Follow the prompts in the text box to the best of your knowlege. Ensure you delete the prompts before writing in them.

### Affected Products

This area includes 4 fields which are listed below. **Leave this area blank if you do not know what packages are affected**

<details><summary>Ecosystem</summary>
<p>

The ecosystem in which the advisory is affected.

</p>
</details> 

<details><summary>Package Name</summary>
<p>

The name of the package.

</p>
</details> 

<details><summary>Affected Versions</summary>
<p>

What versions of the product are listed in the change to the package.

</p>
</details> 

<details><summary>Patched Versions</summary>
<p>

What version is the most up-to-date of the package.

</p>
</details> 

### Severity

For this dropdown, select the severity that you would deem this advisory is. If you know the vulnerability vectors, use the `Calculator` feature below.

### Weaknesses

In this text box you can input a Common Weakness Enumeration (CWE) value. You can find a full list of CWEs in [this gist](https://gist.github.com/zaghaghi/e8541046020f7eb61933edb95f6753d9).

### Credits

In this field, write the names, emails, usernames, etc. of people who contributed to this advisory.

When you are finished, select the green `Create Draft Security Advisory` button
**Remember, this advisory is not going to be introduced to the public unless it is deemed fit to do so. Details you request not to be shared are not shared with the public unless they are vital to the security vulnerability.**

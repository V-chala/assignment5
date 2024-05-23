# assignment5

have written the parts of resume in JSON Format as given in the task page of assignment.



# task 2: Write conditions for the Above JSON data: 

# For Loop:

Used to iterate over the skills array.
for (let i = 0; i < resume.skills.length; i++) { ... } iterates through each element in the array.

# For...In Loop:

Used to iterate over the properties of the resume object.
for (let key in resume) { ... } iterates over all enumerable properties of the object.

# For...Of Loop:

Used to iterate over the responsibilities array of the first experience.
for (let responsibility of resume.experience[0].responsibilities) { ... } iterates through each value in the iterable object.

# ForEach Loop:

Used to iterate over the certifications array.
resume.certifications.forEach(certification => { ... }) executes the provided function once for each array element.

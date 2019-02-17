
# Submission Rules and Guidelines

All submissions and appeals regarding the exercise, must be sent to `mobile.shenkar.s19@gmail.com`
<br>
(all other channels will be ignored)

For specific inquiries regarding a given exercise, please open new issue with the following title template:<br>
`[Ex0<num>]: <question_body>`

Example: `[Ex01]: Can we use third party library to implement XYZ algorithm?`

**Please do not tend to answer other people's questions, to make sure no one is misleading the others.
I will answer the issues and close them. Make sure to review issues as my answers there will be applied to all of you.**

## General Guidelines & Code Review Criteria
1. Code must be written according to the Coding Standards defined by default `eslint` rules for `JavaScript`, `React` and `React-Native`.
Make sure to install and run those plugins by following the [eslint guide](./eslint.md)
2. Define meaningful variable and function names. Your code should be simple, clear and readable.
3. Comments are NOT welcome. I want to read code! Use comments only to explain some odd decision or explain some hard-to-read algorithm.
4. Do not use extra empty new-lines.
5. Do not submit not-working/compiling code.
6. Do not submit dead code (code block which never runs).
7. Your code should be well indented and organized.
8. Your code should be well design, divided to modules and functions. Properly using software engineering principles of reusability, inheritance (or mixin), composition and polymorphism.
9. Your code should implement covered topics functionality, though enhancements are always welcome!


## Submission Rules
1. Submit in pairs ***ONLY***<br>
(No, I don't care if you're a gang since the kindergarden)
2. You MUST submit on time!
    * MILUIM is an exception, if you provide a "release from service" (מכתב שחרור) note.
    * First relation medical hospitality is an exception.<br>

    In case you need to use one of the above exceptions, please contact me in person BEFORE the submission due date. You will not be scored until you provide proper documentation.<br>
    Any late submission that was not approved in advanced will lead to 10%-100% score penalty.

## What should be submitted?
1. The file you submit must be in the following format:<br>
`Ex0<num>_FirstStudentFullName_<studentId>_SecondStudentFullName_<studentId>.zip`

    For Example: `Ex01_JimiHendrix_011112222_GaryNuman_033334444.zip`
2. The file must be compressed in `zip` format and ends with `.zip` extension.
3. The following folders must not be included:
    * `node_modules`
    * `./ios/build`
    * `./android/build`
    * `./android/.idea`
    * `./android/.gradle`
    * `./android/*.iml`

4. If you followed the the previous bullets correctly, the resulted `.zip` file size should be very small (less than 2MB)
5. In your project's `package.json` file, you must add your details in the following schema:
```
"checkSubmission": {
    "ex": Number,
    "students": [
        {"id": "string", "fullName": "string", "email": "string"}
        {"id": "string", "fullName": "string", "email": "string"}
    ],
    "os": "string", // one of [Mac, Linux, Windows]
    "device": "string", // one of [Android, iOS]
    "deliveryDate": "string", // in format MM/DD/YYYY,
    "delay": Boolean,
    "delayReason": "string",
    "comments": "string"
}
```
For Example:
```json
"checkSubmission": {
    "ex": "1",
    "students": [
      {
        "id": "011112222",
        "fullName": "Jimi Hendrix",
        "email": "jimi@hendrix.com"
      },
      {
        "id": "033334444",
        "fullName": "Gary Numan",
        "email": "gary@numan.com"
      }
    ],
    "os": "Mac",
    "device": "iOS",
    "deliveryDate": "03/13/2018",
    "delay": true,
    "delayReason": "Not enough time.",
    "comments": "Feature number 4 works only when running in debug mode."
  }
```

## How to submit?
Moodle...


## Exercise Check & Report
1. If you did not get any response to confirm your submission within 48 hours, please ping me.
2. When checking is over, you will receive an email with the score and the check report.
3. If you will get the source code back, you should look for my comments in the code (use `find` to look for `$Review$:`).
4. The response email will be sent as `Reply All` to sender.
5. For any kind of communication regarding your exercise submission, use the following formats:
* For submission: `SUBMIT <zip_filename_format_as_mentioned_above_WITHOUT_ZIP_EXTENSION>`
* For inquiry: `QUESTION <zip_filename_format_as_mentioned_above_WITHOUT_ZIP_EXTENSION>`
* For Appealing: `RECHECK <zip_filename_format_as_mentioned_above_WITHOUT_ZIP_EXTENSION>`



**Note:**
Any kind of violence of this document guidelines - will lead to score punishment
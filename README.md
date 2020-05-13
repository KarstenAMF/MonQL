# MonQL
http://monql.herokuapp.com/

MonQL is a transpiler for harmonizing NoSQL MongoDB Mongoose schemas with their GraphQL counterparts. The paper describes how with methods of compilers/transpilers MonQL has been developed with the help of the popular parser generator ANTLR. Starting out with a formal grammar, it is shown how a single schema defniton can result in different JavaScript outputs for Mongoose and GraphQL. With a generated WalkTree-Listener by ANTLR the process of constructing individual transpiled code for different uses will be described. As a result a single MonQL files content can be automatically transpiled to JavaScript for the MongoDB ODM and the GraphQL API.
(taken from the abstract of my unreleased MonQL paper)


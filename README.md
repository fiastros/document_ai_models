TODO

- [ ] Test deepdoctection for key information extraction
- [ ] Test docquery
- [ ] Test donut (document understanding)
- [ ] Find or retrain donut on french documents (huggingface, kaggle, github ...)
- [ ] have got to consider the orientation of the document
- [ ] got to pre-process the document

Task to perform  

- [ ] Invoice Date (purchase date)
- [ ] Expense category
- [ ] Document type
- [ ] Currency
- [ ] purchase time
- [ ] total including taxes
- [ ] Taxes
- [ ] Supplier (names, address)
- [ ] sender/receiver email address
- [ ] url/website/number
- [ ] demander à perplexity si deepdoctection permet d'avoir les Kie ou bien il faut rajouter un llm (lui donner un json organisé)

detection of objects of interrest (technically doctr kie could do it...)


correctemenet configuer et utiliser un modèle de table: 
https://deepdoctection.readthedocs.io/en/latest/tutorials/analyzer_with_table_transformer_notebook/

dataset on invoices: 

Yes, I'm aware of a few open-source databases that contain invoices and could be used to train named entity recognition (NER) models. Here are a few options:

1. **INvoice GErmanaN (IGN) dataset**: This dataset contains around 1,000 German invoices, and was created for the purpose of NER and information extraction tasks. You can find the dataset and more information on the project's GitHub page: <https://github.com/sd-web/ign>
2. **Financial Document Parsing (FDP) dataset**: This dataset contains around 3,000 financial documents, including invoices, and was created for the purpose of information extraction tasks. You can find the dataset and more information on the project's GitHub page: <https://github.com/dbtsevis/financial-document-parsing>
3. **FUNSD dataset**: This dataset contains 199 fully annotated, scanned documents (invoices, letters, forms, etc.) and was created for the purpose of form understanding tasks. You can find the dataset and more information on the project's GitHub page: <https://github.com/gerb/funsd>

These datasets can be used to train NER models specifically 
for invoices, or you can use them to train more general NER 
models that can handle various types of financial documents. Keep in 
mind that you might need to preprocess and clean the data to suit your 
specific needs.


Translate english or german invoice to french.

14min47sec
28min51sec
44min17sec
1h38min42sec
1h39min10sec
2h26min00sec
2h37min50sec
2h55min45sec ++
2h57h50sec
3h01h32sec +++
3h03min53sec +






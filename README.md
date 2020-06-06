# LinearAlgebraInIR
Linear Algebra in Information Retrieval
The advent of Internet and subsequent widespread access to it has dramatically
changed the way in which we create, process and manage documents online.
Both, the scale and the methods of storing and querying documents poses a
unique challenge today.
The manual methods of indexing are succumbing to problems of both capacity and consistency. There are nearly 1.4 million books in print in the United
States alone, with approximately 60,000 new titles appearing there annually.
The experience and opinions of the indexer can significantly affect the extraction and documentation of key words. Experiments have shown that there is
a 20% disparity on average in the terms chosen as appropriate to describe a
given document by two different professional indexers. Automated methods
of Information retrieval arrived to conquer these specific challenges. However
these methods have their own problems, complexities of language being one of
them(polysemy and synonymy).
In Vector Space Model, documents are stored as vectors whose components
determine the importance of that term in reflecting its semantics. The document vectors are stored as columns of a matrix called term-document matrix.
The user’s query is modelled as a vector and compared to the term-document
matrix using cosine similarities. The new document or a new term can be added
by appending the matrix with a new column or new row respectively. QR factorization and SVD is then used for geometric interpretation of vector space
model and for rank reduction of the term-document matrix to account for the
uncertainties in the database. The two factorization methods are then compared
for their specific benefits.

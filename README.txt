This is the stub README.txt for the "kgn" project.

try:

    (ql:quickload "kgn-common")
    (kgn-common:dbpedia-get-company-detail "<http://dbpedia.org/resource/Microsoft>")
    (kgn-common::get-name-and-description-for-uri "<http://dbpedia.org/resource/Apple_Inc.>")


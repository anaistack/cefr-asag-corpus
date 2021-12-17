|copy| 2017 by ALTISSIA International s.a.

CEFR-ASAG CORPUS
================

.. image:: https://img.shields.io/badge/version-1.0.0-blue
   :target: https://github.com/anaistack/cefr-asag-corpus/tree/main
   :alt: package version

This dataset contains a number of short texts written by non-native speakers 
of English. Each participant was asked to provide a short answer to an 
open-ended question which targeted the proficiency level in which he/she was
placed. Each question is therefore labelled with a particular proficiency level,
as defined by the Common European Framework of Reference for Languages (CEFR).

Moreover, 299 of the collected answers were also labelled using the CEFR, by
a panel of three CEFR-certified examiners. Their labels, as well as a 
majority-vote label, have been added to each one of these texts.

All texts are encoded in a TEI format.

More information can be found in the following `paper <https://aclanthology.org/W17-5018>`_. 
When using the data in your research or publication, please cite this work as well.

.. code-block:: latex
   
   @inproceedings{tack-etal-2017-human,
       title = {Human and Automated {CEFR}-based Grading of Short Answers},
       author = {Tack, Ana{\"\i}s and Fran{\c{c}}ois, Thomas and Roekhaut, Sophie and Fairon, C{\'e}drick},
       booktitle = {Proceedings of the 12th Workshop on Innovative Use of {NLP} for Building Educational Applications},
       month = sep,
       year = {2017},
       address = {Copenhagen, Denmark},
       publisher = {Association for Computational Linguistics},
       url = {https://aclanthology.org/W17-5018},
       doi = {10.18653/v1/W17-5018},
       pages = {169--179}
   }


Authors
-------

* ALTISSIA International s.a. - www.altissia.com
* Center for Natural Language Processing (CENTAL), Université catholique de Louvain (UCL, Belgium) - cental@uclouvain.be


License
-------

This work is licensed under a 
Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.

You should have received a copy of the license along with this
work.  If not, see http://creativecommons.org/licenses/by-nc-sa/4.0/.

See LICENSE.txt for more details.


Changelog
---------

All notable changes to this project will be documented in this file.

The format is based on `Keep a Changelog <https://keepachangelog.com/en/1.0.0/>`__,
and this project adheres to `Semantic Versioning <https://semver.org/spec/v2.0.0.html>`__.

[1.0.1] - 2017-10-16
~~~~~~~~~~~~~~~~~~~~

Fixed
   - All personal details have been anonymized using the following tags:
     + {name}: first or full names
     + {initial}: name initials
     + {number}: phone numbers

[1.0.0] - 2017-09-08
~~~~~~~~~~~~~~~~~~~~

Added
   - First release of the dataset

.. |copy|   unicode:: U+000A9 .. COPYRIGHT SIGN
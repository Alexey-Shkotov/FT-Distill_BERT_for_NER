# FT-Distill_BERT_for_NER
Finetuning Pre-Trained BERT for Named Entity Recognition tasks and distillation it

- В этом проекте я решал задачу Named Entity Recognition (NER) на самом популярном датасете – CoNLL-2003. В моём распоряжении предобученный BERT, который необходимо уменьшить без потерь в качестве.
- Дообучил BERT на задачу NER.
- Реализовал метод дистилляции знаний. Для подсчета ошибки между предсказаниями ученика и учителя использовал KL-дивергенцию

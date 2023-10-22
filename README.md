# miphi_chem

решение хакатона МИФИ по Хемоинформатике на предсказание того, является ли молекула лекарством или нет

скор бейзлана r2=0.05

chem_tda - чисто топологические методы, r2=0.08

chem_ml - mol2vec + stacking (catboost, knn, lasso) - лучший скор: r2=0.26

chem_ml - обогащение + mol2vec + stacking (catboost, knn, lasso) - лучший скор: r2=0.48

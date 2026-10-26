Analysis basis: raw N=540; complete-case PLS N=537; valid discipline N=535.
Compared Q14-Q26 numeric values row-wise against SmartPLS_final_numeric.csv: all match.
Exploratory tests: Kruskal-Wallis omnibus (Holm across 6 outcomes); Mann-Whitney post-hoc (Holm within each outcome, BH globally); rank-biserial r; Spearman rho (BH across 16).
All p-values are two-sided. Kruskal-Wallis H uses tie correction from scipy. No inferential causal claims.
Screening duplicate excludes timestamp by comparing all other raw answers. Duplicate flags do NOT establish repeat submission.
Questionnaire measures Q19 saving attempt and Q26 future-security orientation, not actual savings amount.
No PLS-SEM re-estimation or SmartPLS sensitivity bootstrap in this script.

OMNIBUS:
{'Outcome': 'FL', 'H': 160.5734, 'df': 3, 'p': np.float64(1.3784062172875442e-34), 'Holm_p': np.float64(8.270437303725265e-34), 'epsilon_sq': 0.2967}
{'Outcome': 'FMB', 'H': 8.5174, 'df': 3, 'p': np.float64(0.0364451682468246), 'Holm_p': np.float64(0.0364451682468246), 'epsilon_sq': 0.0104}
{'Outcome': 'ISB', 'H': 18.4335, 'df': 3, 'p': np.float64(0.00035796360668815614), 'Holm_p': np.float64(0.0017898180334407806), 'epsilon_sq': 0.0291}
{'Outcome': 'SI', 'H': 17.6488, 'df': 3, 'p': np.float64(0.0005196420496467753), 'Holm_p': np.float64(0.002078568198587101), 'epsilon_sq': 0.0276}
{'Outcome': 'Q19', 'H': 11.1383, 'df': 3, 'p': np.float64(0.011001102937120994), 'Holm_p': np.float64(0.022002205874241988), 'epsilon_sq': 0.0153}
{'Outcome': 'FFO', 'H': 14.8276, 'df': 3, 'p': np.float64(0.001970082356230963), 'Holm_p': np.float64(0.005910247068692889), 'epsilon_sq': 0.0223}

SIGNIFICANT PAIRWISE (Holm within outcome < .05):
{'Outcome': 'FL', 'Group_A': 'Arts/Humanities', 'Group_B': 'Business/Commerce', 'n_A': 120, 'n_B': 146, 'mean_A': 2.2, 'mean_B': 4.2534, 'U': 2313.0, 'rank_biserial': -0.736, 'p': np.float64(1.2539732867247754e-26), 'Holm_within_outcome_p': np.float64(7.523839720348653e-26), 'BH_all_pairs_p': np.float64(4.514303832209192e-25)}
{'Outcome': 'FL', 'Group_A': 'Arts/Humanities', 'Group_B': 'Science/Engineering', 'n_A': 120, 'n_B': 156, 'mean_A': 2.2, 'mean_B': 2.8974, 'U': 6636.5, 'rank_biserial': -0.291, 'p': np.float64(1.7160293487800213e-05), 'Holm_within_outcome_p': np.float64(5.1480880463400635e-05), 'BH_all_pairs_p': np.float64(0.0001544426413902019)}
{'Outcome': 'FL', 'Group_A': 'Business/Commerce', 'Group_B': 'Medical/Health', 'n_A': 146, 'n_B': 113, 'mean_A': 4.2534, 'mean_B': 2.4336, 'U': 13895.0, 'rank_biserial': 0.6844, 'p': np.float64(9.92502353580144e-23), 'Holm_within_outcome_p': np.float64(4.96251176790072e-22), 'BH_all_pairs_p': np.float64(1.786504236444259e-21)}
{'Outcome': 'FL', 'Group_A': 'Business/Commerce', 'Group_B': 'Science/Engineering', 'n_A': 146, 'n_B': 156, 'mean_A': 4.2534, 'mean_B': 2.8974, 'U': 18010.0, 'rank_biserial': 0.5815, 'p': np.float64(7.965019374317406e-20), 'Holm_within_outcome_p': np.float64(3.1860077497269625e-19), 'BH_all_pairs_p': np.float64(9.558023249180888e-19)}
{'Outcome': 'FL', 'Group_A': 'Medical/Health', 'Group_B': 'Science/Engineering', 'n_A': 113, 'n_B': 156, 'mean_A': 2.4336, 'mean_B': 2.8974, 'U': 6989.5, 'rank_biserial': -0.207, 'p': np.float64(0.002621536385703318), 'Holm_within_outcome_p': np.float64(0.005243072771406636), 'BH_all_pairs_p': np.float64(0.007864609157109953)}
{'Outcome': 'FMB', 'Group_A': 'Business/Commerce', 'Group_B': 'Science/Engineering', 'n_A': 146, 'n_B': 156, 'mean_A': 3.3607, 'mean_B': 3.0491, 'U': 13462.5, 'rank_biserial': 0.1822, 'p': np.float64(0.005976263871234969), 'Holm_within_outcome_p': np.float64(0.03585758322740981), 'BH_all_pairs_p': np.float64(0.016549653797266067)}
{'Outcome': 'ISB', 'Group_A': 'Arts/Humanities', 'Group_B': 'Business/Commerce', 'n_A': 120, 'n_B': 146, 'mean_A': 2.8, 'mean_B': 3.2808, 'U': 6487.0, 'rank_biserial': -0.2595, 'p': np.float64(0.00025328267239753193), 'Holm_within_outcome_p': np.float64(0.0013296729820346778), 'BH_all_pairs_p': np.float64(0.0013025966009015926)}
{'Outcome': 'ISB', 'Group_A': 'Arts/Humanities', 'Group_B': 'Medical/Health', 'n_A': 120, 'n_B': 113, 'mean_A': 2.8, 'mean_B': 3.2596, 'U': 5107.0, 'rank_biserial': -0.2468, 'p': np.float64(0.0010859226052417426), 'Holm_within_outcome_p': np.float64(0.00434369042096697), 'BH_all_pairs_p': np.float64(0.003909321378870273)}
{'Outcome': 'ISB', 'Group_A': 'Arts/Humanities', 'Group_B': 'Science/Engineering', 'n_A': 120, 'n_B': 156, 'mean_A': 2.8, 'mean_B': 3.2671, 'U': 6944.0, 'rank_biserial': -0.2581, 'p': np.float64(0.0002216121636724463), 'Holm_within_outcome_p': np.float64(0.0013296729820346778), 'BH_all_pairs_p': np.float64(0.0013025966009015926)}
{'Outcome': 'SI', 'Group_A': 'Arts/Humanities', 'Group_B': 'Medical/Health', 'n_A': 120, 'n_B': 113, 'mean_A': 3.2028, 'mean_B': 3.6401, 'U': 5037.0, 'rank_biserial': -0.2571, 'p': np.float64(0.0006480273467317783), 'Holm_within_outcome_p': np.float64(0.0032401367336588917), 'BH_all_pairs_p': np.float64(0.002756447282423686)}
{'Outcome': 'SI', 'Group_A': 'Arts/Humanities', 'Group_B': 'Science/Engineering', 'n_A': 120, 'n_B': 156, 'mean_A': 3.2028, 'mean_B': 3.6581, 'U': 6775.5, 'rank_biserial': -0.2761, 'p': np.float64(7.306949454621621e-05), 'Holm_within_outcome_p': np.float64(0.0004384169672772973), 'BH_all_pairs_p': np.float64(0.0005261003607327566)}
{'Outcome': 'Q19', 'Group_A': 'Business/Commerce', 'Group_B': 'Science/Engineering', 'n_A': 146, 'n_B': 156, 'mean_A': 3.9863, 'mean_B': 3.5769, 'U': 13660.5, 'rank_biserial': 0.1996, 'p': np.float64(0.0015658213093762933), 'Holm_within_outcome_p': np.float64(0.00939492785625776), 'BH_all_pairs_p': np.float64(0.005124506103413324)}
{'Outcome': 'FFO', 'Group_A': 'Business/Commerce', 'Group_B': 'Medical/Health', 'n_A': 146, 'n_B': 113, 'mean_A': 3.911, 'mean_B': 3.6195, 'U': 9748.0, 'rank_biserial': 0.1817, 'p': np.float64(0.007908281952247968), 'Holm_within_outcome_p': np.float64(0.039541409761239835), 'BH_all_pairs_p': np.float64(0.020335582162923343)}
{'Outcome': 'FFO', 'Group_A': 'Business/Commerce', 'Group_B': 'Science/Engineering', 'n_A': 146, 'n_B': 156, 'mean_A': 3.911, 'mean_B': 3.5128, 'U': 13824.0, 'rank_biserial': 0.2139, 'p': np.float64(0.0006891118206059215), 'Holm_within_outcome_p': np.float64(0.004134670923635529), 'BH_all_pairs_p': np.float64(0.002756447282423686)}

WITHIN-GROUP CORRELATIONS:
{'Group': 'Arts/Humanities', 'n': 120, 'Comparison': 'FL vs FMB', 'rho': -0.031, 'p': np.float64(0.7371704632375694), 'BH_16_tests_p': np.float64(0.7863151607867407)}
{'Group': 'Arts/Humanities', 'n': 120, 'Comparison': 'FL vs ISB', 'rho': 0.0339, 'p': np.float64(0.7134149921451254), 'BH_16_tests_p': np.float64(0.7863151607867407)}
{'Group': 'Arts/Humanities', 'n': 120, 'Comparison': 'FL vs SI', 'rho': 0.0312, 'p': np.float64(0.7353087975556027), 'BH_16_tests_p': np.float64(0.7863151607867407)}
{'Group': 'Arts/Humanities', 'n': 120, 'Comparison': 'FL vs FFO', 'rho': -0.1044, 'p': np.float64(0.25629341093784097), 'BH_16_tests_p': np.float64(0.4882738632442167)}
{'Group': 'Business/Commerce', 'n': 146, 'Comparison': 'FL vs FMB', 'rho': 0.0802, 'p': np.float64(0.33596976669151973), 'BH_16_tests_p': np.float64(0.5375516267064315)}
{'Group': 'Business/Commerce', 'n': 146, 'Comparison': 'FL vs ISB', 'rho': -0.0488, 'p': np.float64(0.5584145044125934), 'BH_16_tests_p': np.float64(0.7863151607867407)}
{'Group': 'Business/Commerce', 'n': 146, 'Comparison': 'FL vs SI', 'rho': 0.1292, 'p': np.float64(0.12014816883656196), 'BH_16_tests_p': np.float64(0.32039511689749856)}
{'Group': 'Business/Commerce', 'n': 146, 'Comparison': 'FL vs FFO', 'rho': 0.1426, 'p': np.float64(0.08605197315498253), 'BH_16_tests_p': np.float64(0.32039511689749856)}
{'Group': 'Medical/Health', 'n': 113, 'Comparison': 'FL vs FMB', 'rho': 0.0426, 'p': np.float64(0.6543382225385082), 'BH_16_tests_p': np.float64(0.7863151607867407)}
{'Group': 'Medical/Health', 'n': 113, 'Comparison': 'FL vs ISB', 'rho': 0.1036, 'p': np.float64(0.27465404807487187), 'BH_16_tests_p': np.float64(0.4882738632442167)}
{'Group': 'Medical/Health', 'n': 113, 'Comparison': 'FL vs SI', 'rho': 0.1796, 'p': np.float64(0.05695515656676063), 'BH_16_tests_p': np.float64(0.32039511689749856)}
{'Group': 'Medical/Health', 'n': 113, 'Comparison': 'FL vs FFO', 'rho': -0.0097, 'p': np.float64(0.9190165134591481), 'BH_16_tests_p': np.float64(0.9190165134591481)}
{'Group': 'Science/Engineering', 'n': 156, 'Comparison': 'FL vs FMB', 'rho': 0.1316, 'p': np.float64(0.1016304344691214), 'BH_16_tests_p': np.float64(0.32039511689749856)}
{'Group': 'Science/Engineering', 'n': 156, 'Comparison': 'FL vs ISB', 'rho': 0.1443, 'p': np.float64(0.07224356788088597), 'BH_16_tests_p': np.float64(0.32039511689749856)}
{'Group': 'Science/Engineering', 'n': 156, 'Comparison': 'FL vs SI', 'rho': 0.1564, 'p': np.float64(0.05118987568878147), 'BH_16_tests_p': np.float64(0.32039511689749856)}
{'Group': 'Science/Engineering', 'n': 156, 'Comparison': 'FL vs FFO', 'rho': 0.0956, 'p': np.float64(0.23512152484914856), 'BH_16_tests_p': np.float64(0.4882738632442167)}

FLAGS: duplicate groups [[72, 73]] straightliners [130, 132]

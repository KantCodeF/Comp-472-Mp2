https://github.com/KantCodeF/Comp-472-Mp2/
# Comp-472-Mp2
Team: the lost child
Team member: Zeying Wu 40257530; Winyul yin 40176217

# How to run the program
## 1. Run all algorithm with 4 heuristic functions with write_sol_files function, it will genererate both search and solution files.

gameboards is the array of initial gameboard configuration, fuel is the array of initial fuel for each gameboard, algo is the type of algorithm used for search, algo_string is the name of the algorithm, h is the heuristic function and h
write_sol_files(gameboards, fuel, algo, algo_string, h, h_string):

#UCS algo
write_sol_files(gameboards, fuel, UCS, 'ucs', None, None)

#h1 to h4 for GBFS algo
write_sol_files(gameboards, fuel, GBFS, 'gbfs', h1, 'h1')
write_sol_files(gameboards, fuel, GBFS, 'gbfs', h2, 'h2')
write_sol_files(gameboards, fuel, GBFS, 'gbfs', h3, 'h3')
write_sol_files(gameboards, fuel, GBFS, 'gbfs', h4, 'h4')

#h1 to h4 for A algo
write_sol_files(gameboards, fuel, A, 'a', h1, 'h1')
write_sol_files(gameboards, fuel, A, 'a', h2, 'h2')
write_sol_files(gameboards, fuel, A, 'a', h3, 'h3')
write_sol_files(gameboards, fuel, A, 'a', h4, 'h4')

## 2. Run all algorithm with 4 heuristic functions with excel_analysis function, it will generate the excel file as instructed in the question pdf.

gameboards is the array of initial gameboard configuration, fuel is the array of initial fuel for each gameboard.
excel_analysis(gameboards,fuel)


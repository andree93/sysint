This dataset contains a set of transactions done on different cash points.
Each row contains the amount of a specific denomination withdrawal/deposited in one cashpoint during a day.
The dataset is used to build an AI model to predict cash orders for the branches.
 
CASHPOINT_ID			The unique identifier of the cashpoint (ATM, CSA)
CO_BANK					The bank identification code
BRANCH_ID				The branch identifier
CO_BRANCH				The branch code (usend internaly)
LOCATION_ID				The location identifier
CO_CASHPOINT			The cashpoint code (usend internaly)
CO_CHANNEL				The type of the machine
CO_LOGISTIC				EXTERNAL/INTERNAL
SUBGROUP				Location subgroup (not used)
FL_EXTERNALIZED			1 if the cashpoint is externalized
FL_INACTIVE				1 if the cashpoint is inactive
FL_IMPORTANT			1 if is a critical cashpoint
TS_ACTIVITY_START		Activity starting date of the cashpoint
ACTIVITY_START			Activity starting date of the branch
TE_CITY					The city in which the cashpoint is installed
DT_REFERENCE			Timestamp of the transaction
QT_OUT					Number of notes withdrawal
QT_IN_L4FIT				Number of L4 Fit deposited notes 
QT_IN_L4UNFIT			Number of L4 Unfit deposited notes 
QT_RECYCLED				Number of recycled notes
QT_L3					Number of L3 deposited notes 
QT_L2					Number of L2 deposited notes 	
VA_DENOMINATION			The denomination
CO_CURRENCY				The currency
CURRENCY_UNIT_ID		The currency identifier
ATM_TYPE				The type of the cashpoint (OUT/REC)
CO_DAY_TYPE				Status of the branch
LOG_INTERNAL			
DT_YEAR					Year
DT_MONTH				Month
DT_QUARTER				Quarter
DT_DAY_OF_WEEK			Day of the week
FL_MISSING				1 if there has not been any movement during the day, 0 otherwise
CP_SHORTAGE_THRESHOLD	minimum amount of money to grant withdrawals, under it cashpoint needs a charge
CP_SURPLUS_THRESHOLD	maximum amount of money to grant deposits, over it cashpoint needs a discharge
SHORTAGE_THRESHOLD		minimum amount of money to grant withdrawals in location, under it location needs a charge
SURPLUS_THRESHOLD		maximum amount of money to grant deposits in location, over it location needs a discharge
QT_OUT_MAX_THRESHOLD	maximum quantity of banknotes inside withdrawal cassette of a cashpoint, over it cassettes must be emptied
QT_OUT_MIN_THRESHOLD	minimum quantity of banknotes inside withdrawal cassette of a cashpoint, over it cassettes must be charged
QT_IN_MAX_THRESHOLD		maximum quantity of banknotes inside deposit cassette of a cashpoint, over it cassettes must be emptied
[MENU](README.md)
<br><br>
[BACK](objects_and_data_structures.md)

# ΕΛΛΙΠΕΙΣ ΤΙΜΕΣ

---

- Για τον έλεγχο ελλιπών τιμών υπάρχουν οι συνάρτησης is.na και is.nan.
- Η τιμή NA ανήκει στην αριθμητική κλάση.
- Η τιμή NaN ανήκει στην λογική κλάση. 

πχ: 	`
	> x <- NA
	> is.na(x)
    	[1] TRUE
	> y <- 0/0
	> y
	[1] NaN
	> is.nan(y)
	[1] TRUE
	`

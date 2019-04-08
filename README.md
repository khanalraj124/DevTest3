# DeveloperTest3

In HomeController.vb -> GetPlayerRanking method, I have replaced where clause with single and also changed the case to lower to avoid case sensitive search. 
Added conditions to set empty values in final result when no values are entered in search box.
If any exception comes, we are displaying the message "Player not found"
Used the ranking value 999999 to meet the condition specified in view where rank should be greater than zero.

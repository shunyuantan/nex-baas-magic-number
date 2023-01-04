# Enrollment Scripts for BaaS 

Here we are using magic numbers in the reference id

Input: @bss-1000
Enrollment Status: Auto-approval flow
Expected KTP Input: 0000 0000 0000 1000

Input: @bss-2000
Enrollment Status: Auto-approval flow going through KK
Expected KTP Input: 0000 0000 0000 2000

Input: @bss-3000
Enrollment Status: Auto-approval flow going through EDD
Expected KTP Input: 0000 0000 0000 3000

Input: @bss-4000
Enrollment Status: Auto-approval flow going through KK + EDD
Expected KTP Input: 0000 0000 0000 4000

Input: @bss-1001
Enrollment Status: Auto-rejection flow
Expected KTP Input: 0000 0000 0000 1001
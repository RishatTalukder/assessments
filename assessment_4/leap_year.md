input year
if year%100 == 0:
    if year%400 == 0:
        output leap year
    else:
        output not leap year
else:
    if year%4==0:
        output leap year
    else:
        output not leap year
end


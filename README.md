# Shift the doctor

`Shift the doctor` is a shift plan creator for hospital doctors.

The tool automatically creates a shift plan based on the follwoing assumptions:

- Shifts last 24 h
- Doctors can have shift wishes
- It distributes the doctors for a month
- Doctors can work part or full time
- It considers vacations
- It distributes shift by maximazing the distance between shifts of each doctor
- It considers that weekends as special times
- There are two assigned doctors per day
- Each doctor is either first or second assistant

As input the tool accepts a csv file with parameters (name, assistant, part time, vacation, shift wishes, non-available times, last_shift).

In the end it outputs an editable excel file.

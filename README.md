# MG Software ReactJS task
The purpose of this task is to better understand applicant's frontend development skills (React/HTML/CSS).

Task is related to Holiday package (flight + hotel + transfer) booking system.

## Requirements
1. Use ReactJS.
2. Use HTML/CSS.
3. Create a private repository and give **mg-code** user access to it.  Then send repository information to e-mail.

## Objective 1
Implement experience of holiday package search form.
1. Form has three filters: Departure city, Destination, Departure dates.
2. All filters depends on previous filter in the same order: Departure city -> Destination -> Departure dates.
3. User can't open filter if previous filter is not filled in. If user tries, then open previous filter.
4. If user tries to submit form and at least one filter is not filled in, then do the same as described in #3.
5. Implement HTML/CSS as in screenshots bellow.
6. You can use same SVG for all flags. Screenshots are informative.
7. You can use any react datepicker package. Datepicker does not need styling.

![Form design](/images/form.png)
![Departure city](/images/departure-city.png)
![Destination](/images/destination.png)
![Departure dates](/images/dates.png)

## Objective 2 (Optional, but good to have)
If user opens filter on mobile device, then show filter in full screen layout.

![Responsive filter](/images/responsive.png)

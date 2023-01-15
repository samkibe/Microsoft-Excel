So, let's say a start up company of around 100+ employees, wants us to create email addresses for its new 100+ employees on their domain @KEMSA.GO.KE (Hey!! if this domain belongs to such, well, all rights belong to them)

Anyways, they write down their names on a two row excel sheet (1st_name & 2nd_name)

The company allows us to utilize the names! awesome!! 💪
Now, we need first to create a 3rd row with their full name, then concatenate stuff 🙄 good thing we have #formulas to do that in #excel.

AND this is where =CONCATENATE() comes in;
SO, for our 3rd row #Full_name we use:-
=CONCATENATE(text1," ",text2) notice the space.. #text denotes #cells

For our 4th row #Emails we use:-
=CONCATENATE(text1,".",text2, "@KEMSA.GO.KE") have you noticed the space? good!!

![image](https://user-images.githubusercontent.com/25104443/212529783-2f1ec21f-7b5b-4658-adca-211e0bd8a79c.png)

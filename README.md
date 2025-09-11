# titanic-survival-study
# Titanic Survival Study — Gurunandhan “Guru” Pillai
**Questions.** Who survived more by gender/class/age? What simple patterns stand out?
**Data.** Public Titanic CSV.
**Approach.** Clean missing values → engineer FamilySize & AgeBand → groupby survival → simple charts → summarize.

## Three Insights
1) Sex: Female survival = 74%, Male survival = 19%
2) Class: 1st Class survival = 63%, 2nd Class = 47%, 3rd Class = 24%
3) Age Group: Children (0–14) had the highest survival = 59%; Adults 30–49 = 42%, Young Adults 15–29 = 34%, Seniors 50+ = 34%
   
## Files
- `titanic.ipynb` — runs end-to-end in Colab
- `titanic_cleaned.csv` — cleaned export
- `/assets` — charts used in the README and for quick portfolio screenshots

## Next Step
Try logistic regression or decision trees to predict survival and compare feature importance.


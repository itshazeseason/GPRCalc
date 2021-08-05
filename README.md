# GPRCalc Jupyter

## Binder Link:

```
https://mybinder.org/v2/gh/itshazeseason/GPRCalc/HEAD
```

## How to Use

1. Run GPRCalc1.py in CityEngine, `cgainput.csv` should be created or updated in the file directory of the GPRCalc python scripts

2. Open the above binder link. It will start up a jupyter notebook environment (it takes a while to create)

3. When the binder is successfully created, it will look like this:

   ![](https://drive.google.com/uc?export=view&id=1hmFSBW7RtAM46z1UTsztCZYWNCdCnahO)

   The binder link is unique per session and will be deactivated if there is no activity for a period of time

4. Upload `cgainput.csv` to the binder by clicking Upload 

   ![](https://drive.google.com/uc?export=view&id=1kO6kd75N3LdjFRKX4LWOSSIYTRAlqN9k)

   ![](https://drive.google.com/uc?export=view&id=1Q-B_mGKWZOczDnlWPhDPYXW0dkqM9EvJ)
   Click the blue Upload button again when ready to upload the file up. It will take a while depending on the file size

5. Open `GPRCalc.ipynb` , the jupiter notebook. 

6. Run the first cell to install the pulp library by selecting the cell (it will be highlighted in blue), then go to Cell > Run Cells. For subsequent uses, you may skip this part

   ![](https://drive.google.com/uc?export=view&id=1eRtn_b2vdWg224ajEhrsIfUG-s8qjvmP)

   ![5](https://drive.google.com/uc?export=view&id=1IjeksDrx4tjZFh0gBifY6yu5E5k6qWDG)

7. Run the 2nd cell using the same method as above, or by simply clicking the run button. The script will read from `cgainput.csv` and write the output to `output.csv`.
   You can observe the 4 different GPR ratios and their optimization status by scrolling to the end of the 2nd cell
   ![](https://drive.google.com/uc?export=view&id=1M9mdm4NakJzr1SJPH2oFPg9uywKQnhXu)

8. Going back to the home page, you will see that `output.csv` is generated. Download the file back into the file directory of the GPRCalc python scripts.

   ![](https://drive.google.com/uc?export=view&id=1e6MAd0v4G6kt1ahxIzSz6ZhAbBGHn-6A)

9. Run `GPRCalc2.py` in CityEngine to transfer the output to the CGA rule file


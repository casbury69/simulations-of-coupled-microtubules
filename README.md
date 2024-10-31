Dual-trap simulations.pxp can be run with Igor Pro 9, which has a free trial and can be downloaded at https://www.wavemetrics.com/software/igor-pro-9.

Dual-trap simulator.txt is a text file copy of the procedure used to run simulations in Dual-trap simulations.pxp for viewing outside of Igor Pro 9.

The update on 10/31/24 fixes a minor bug in the calculation of tip separations. It also updates the survival curves from in vitro dual-trap data to account for series compliance of our in vitro bead-kinetochore-microtubule-coverslip system. Please see the following .pdf for details.

[Update to dual-trap data and simulations.pdf](https://github.com/user-attachments/files/17593824/Update.to.dual-trap.data.and.simulations.pdf)

The update on 10/31/24 also changed the calculation of survival curves and corresponding error estimates to correct a very minor error where we should have used the 'at risk' population before a given timestep and instead used the 'at risk' population after that timestep. However, given that each timestep was only 1 second, the changes to survival plots from these updates were barely visible and so were not discussed in the above .pdf.

# Smart-water-networks
This is the source code of the work carried out by D. Fiorillo, G. Galuppini, E. Creaco, F. De Paola and M. Giugni, aimed at identifying the allocation of smart water meters for an accurate reconstruction of the total district water demand pattern.
It is based on a italian case study including measured water demand time series from 1406 users (residential and non-residential) over 1 year of data. All data are confidential.

The codes (written in Matlab) are divided in 2 main folders:

Procedure 1: it enables assessment of the minimum number of users to be monitored starting from the available measured demand time series; it is based on the forward stepwise regression including two different stopping criteria, the Fisher test and the setting of the maximum model order.

Procedure 2: it allows to identify the users to be monitored starting from users’ billed annual demand; it includes different criteria for users selection and a linear model parameterized on the basis of the billed annual demands.  

For further explanations make reference to Fiorillo, D., Galuppini, G., Creaco, E., De Paola, F. and Giugni, M. Identification of influential user locations for smart meter installation to reconstruct the urban demand pattern. Journal of Water Resources Planning and Management (accepted).

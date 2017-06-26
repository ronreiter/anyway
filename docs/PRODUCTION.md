Our production server at www.anyway.co.il is hosted on DigitalOcean.
It is managed by Yehuda Deutsch.
<<<<<<< HEAD

To load new data from the CBS,

1. Request to be added to DigitalOcean of the Public Knowledge Workshop
2. Find the IP address of web1.anyway.co.il
3. Copy the new zip file to the server using SCP
4. Connect to the server using SSH
5. Clone the ANYWAY repository in your home directory and `cd` to it
6. Set `DATABASE_URL` to the URL for the production DB
7. Unzip the new zip file to `static/data/new/Accident Type 3`
8. Run `python process.py --path static/data/new`
=======
>>>>>>> 66e54fad814fc70937ffa38c4dde376148dcd9a8

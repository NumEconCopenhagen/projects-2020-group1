<<<<<<< HEAD
=======
#Initiate figure
fig = plt.figure()
ax = fig.add_subplot(1,1,1)

#Plotting consumptio and labor against wages
ax.plot(w_vec, lab, ls = '--', lw = 2, color = 'black', label = 'labour')
ax.plot(w_vec, con, ls = '-', lw = 2, color = 'blue', label = 'consumption')

#Formatting the visual presentation
ax.set_xlabel('wages')
ax.set_ylabel('labour & consumption')
ax.set_title('Labour and consumption plotted against wages')
ax.grid(True)
ax.legend(loc = 'upper left')

>>>>>>> 5f78c3b7829920305dbccb5c946288aaa5b11288

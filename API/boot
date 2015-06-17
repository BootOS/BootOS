local window = "                                                    "

function boot()
	for i=1,3 do
		term.setCursorPos(1,4)
		term.write("Loading   ")
		sleep(0.5)
		term.setCursorPos(1,4)
		term.write("Loading.  ")
		sleep(0.5)
		term.setCursorPos(1,4)
		term.write("Loading.. ")
		sleep(0.5)
		term.setCursorPos(1,4)
		term.write("Loading...")
		sleep(0.5)
	end
end

function Lwindow()
	for i=1,19 do
		term.setBackgroundColor(colors.gray)
		term.setCursorPos(1,i)
		term.write(window)
		sleep(0.01)
		term.setBackgroundColor(colors.white)
		term.setCursorPos(1,i)
		term.write(window)
	end
end

function loados()
	term.setCursorPos(16,8)
	term.setBackgroundColor(colors.gray)
	term.write("                    ")
	term.setCursorPos(16,9)
	term.write("                    ")
	term.setCursorPos(16,10)
	term.write("                    ")
	term.setCursorPos(16,11)
	term.write("                    ")
	term.setBackgroundColor(colors.lightGray)
	for i=0,15 do
		term.setCursorPos(18+i,9)
		sleep(math.random(0,1))
		term.write(" ")
	end
end

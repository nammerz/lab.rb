lab.rb
======
def has_lab(string)
	if /lab/i.match(string)
		puts "hazzah lab is in the word #{string}!!"
	else
		puts "pft, what a boring word"
	end

end

has_lab("laboratory")
has_lab("experiment")
has_lab("pans Labyrinth")
has_lab("elaborate")
has_lab("polar bear")

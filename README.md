# elixir-notes

#insatll elixir in mac with
brew update
brew install elixir

#check elixir version
elixir -v

#Starts Erlang rutine system
  erl
#interactive shell
 iex

#run elixir program
elixir counter.exs

#mix is a tool to build applications

#mix help
mix -h

#create new proyect
mix new counter

vim mix.exs
#run tests
mix test 

#generate executable file
mix excript.build
./counter

#run iex and load mix configurtions
iex -S mix

#phoenix is a framework to build web services and web applications
#install with
mix local.hex
mix archive.install https://github.com/phoenixframework/archives/raw/master/phoenix_new.ez

#create web application
mix phoenix.new --no-brunch test
#to run phoenix application, perare db in postgress 
mix ecto.create
mix ecto.midrate

#run aplication
iex -S mix phoenix.server

#you can find libraries here
https://hex.pm/packages/xlsxir

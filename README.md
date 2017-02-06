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

#sun iex and load mix configurtions
iex -S mix

mix local.hex
mix archive.install https://github.com/phoenixframework/archives/raw/master/phoenix_new.ez
mix phoenix.new --no-brunch test
mix ecto.create
mix ecto.midrate
iex -S mix phoenix.server
